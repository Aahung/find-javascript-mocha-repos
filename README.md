# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:48 09/16/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43564 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41319 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40190 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30290 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26519 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24624 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24517 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23554 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20081 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19168 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17323 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16971 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16907 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15428 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14383 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14143 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13779 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13306 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12915 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12716 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12414 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12247 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12098 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11636 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11421 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11380 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10645 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10330 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10270 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10199 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10116 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10062 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9906 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9887 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 9571 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9444 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9275 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9217 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9071 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8855 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8841 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8822 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8598 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8570 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8540 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8460 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8355 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8217 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8205 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8101 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8020 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7932 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7788 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7764 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7561 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7461 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7358 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7342 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7329 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7189 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7123 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7106 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7104 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6954 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6837 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6775 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6724 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6587 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6542 | `npm run jshint && mocha test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6483 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6316 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6311 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6263 | `npm run test:mocha:src` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5874 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5873 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5772 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5762 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5758 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5747 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5590 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5441 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5436 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5424 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5420 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5441 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5436 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5424 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5420 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5181 | `mocha src/**/*Tests.js --harmony` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5163 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5146 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5139 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5089 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5003 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4864 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4861 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4800 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4775 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4766 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4752 | `mocha -R spec 'tests/app'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4719 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4701 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4674 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4576 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4538 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4519 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4513 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4496 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4449 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4448 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4346 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4329 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4227 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4216 | `mocha -R spec ./test --recursive` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4210 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4165 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4115 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4094 | `mocha --timeout=15000 tests/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4082 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4060 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4050 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4047 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4047 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4006 | `mocha --require should --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3985 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3977 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3958 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3926 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3920 | `mocha --check-leaks --reporter spec --bail` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3902 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3876 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3771 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3687 | `npm run build && mocha test/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3684 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3676 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3607 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3594 | `NODE_ENV=test mocha --exit` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3585 | `mocha tests/javascript` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3576 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3570 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3547 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3540 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3524 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3497 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3468 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3497 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3468 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3432 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3324 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3313 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3296 | `nyc mocha && tsc` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3154 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3154 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3136 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3133 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3105 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3103 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3102 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3099 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3081 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3079 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3070 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3047 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3032 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3031 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3009 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2968 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2956 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2952 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3047 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3032 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3032 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3031 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3009 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2968 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2956 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2952 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2917 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2915 | `mocha -R landing test/index` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2910 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2907 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2906 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2894 | `eslint . && mocha -t 5000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2889 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2877 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2870 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2867 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2863 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2841 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2830 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2816 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2815 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2809 | `mocha test-node` | 
| [mde/ejs](https://github.com/mde/ejs) | 2801 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2793 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2787 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2777 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2754 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2735 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2726 | `xo && mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2725 | `mocha test.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2716 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2605 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2580 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2578 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2551 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2527 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2497 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2491 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2487 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2486 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2472 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2471 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2459 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2452 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2362 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2359 | `mocha test && npm run lint` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2358 | `mocha test/ --no-timeouts` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2356 | `grunt jshint && mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2351 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2337 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2323 | `mocha && eslint .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2278 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2362 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2359 | `mocha test && npm run lint` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2358 | `mocha test/ --no-timeouts` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2356 | `grunt jshint && mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2351 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2337 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2323 | `mocha && eslint .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2287 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2278 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2244 | `mocha -R spec test/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2233 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2220 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2193 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2156 | `cross-env BABEL_ENV=test mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2147 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2134 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2129 | `standard && mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2125 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2123 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2118 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2109 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2107 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2099 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2088 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2072 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2048 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2048 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2005 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2000 | `npm run lint && npm run mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1996 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1993 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1971 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1971 | `mocha --require=test/test_helper.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1966 | `mocha --reporter spec --timeout 5000` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1957 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1956 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1948 | `npm run lint && mocha -R dot && npm run cover` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1948 | `npm run lint && mocha -R dot && npm run cover` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1942 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1942 | `mocha --bail --reporter spec --check-leaks test/` | 
| [then/promise](https://github.com/then/promise) | 1937 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1932 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1927 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1921 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1914 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1909 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1886 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1882 | `npm run mocha && npm run karma` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1823 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1816 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1815 | `npm run lint && mocha --reporter spec test/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1809 | `mocha --reporter spec --grep .` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1784 | `npm run lint && npm run mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1771 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1764 | `mocha test -u bdd -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1754 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1742 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1736 | `mocha ./test/basic.js -t 5000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1735 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1729 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1784 | `npm run lint && npm run mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1771 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1764 | `mocha test -u bdd -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1754 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1742 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1736 | `mocha ./test/basic.js -t 5000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1735 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1729 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1678 | `mocha test` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1673 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1669 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1669 | `xo && mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1651 | `mocha test/setup.js test/spec/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1641 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1639 | `mocha && size-limit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1637 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1634 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1613 | `mocha tests.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1611 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1651 | `mocha test/setup.js test/spec/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1641 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1639 | `mocha && size-limit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1637 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1634 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1613 | `mocha tests.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1611 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1607 | `eslint --cache . && tsc && mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1601 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1600 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1599 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1545 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1542 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1537 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1536 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1516 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1515 | `nyc mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1513 | `mocha -u tdd` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1512 | `mocha --recursive` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1468 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1460 | `TEST=all mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1451 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1442 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1431 | `mocha --check-leaks --require @babel/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1420 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1414 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1451 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1442 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1431 | `mocha --check-leaks --require @babel/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1429 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1427 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1421 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1420 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1414 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1410 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1405 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1399 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1399 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1398 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1396 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1394 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1392 | `istanbul cover _mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1389 | `npm run lint && mocha && karma start --single-run` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1387 | `./node_modules/mocha/bin/mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1381 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1380 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1379 | `npm run build && mocha -r should` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1373 | `NODE_ENV=test mocha tests/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1368 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1366 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1364 | `mocha tests/test-*` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1355 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1350 | `standard && istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1343 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1338 | `mocha --reporter dot` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1337 | `mocha --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1334 | `mocha -R spec ./test/unit/**` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1332 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1329 | `mocha ./test/test*.js --reporter spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1329 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1317 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1311 | `NODE_PATH=. mocha **/*.spec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1304 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1303 | `mocha spec/exec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1301 | `npm run lint && npm run mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1297 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1296 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1297 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1296 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1294 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1288 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1286 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1285 | `mocha --timeout 60000 test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1281 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1280 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1277 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1270 | `mocha --check-leaks --reporter spec --bail test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1269 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1267 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1266 | `mocha test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1262 | `npm run prepublishOnly && mocha test/test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1261 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1255 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1255 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1250 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1247 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1243 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1242 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1240 | `mocha src/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1236 | `mocha --recursive test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1234 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1233 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1230 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1227 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1225 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1224 | `istanbul test _mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1155 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1155 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1152 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1151 | `npm run mocha:istanbul` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1134 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1129 | `istanbul cover _mocha test/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1129 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1126 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1115 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1114 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1112 | `mocha test/*` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1160 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1155 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1155 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1152 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1151 | `npm run mocha:istanbul` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1134 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [router5/router5](https://github.com/router5/router5) | 1133 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1129 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1126 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1124 | `mocha --timeout 20000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1119 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1134 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [router5/router5](https://github.com/router5/router5) | 1133 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1129 | `istanbul cover _mocha test/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1129 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1126 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1124 | `mocha --timeout 20000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1119 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1115 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1114 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1112 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1111 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1108 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1107 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [electron/asar](https://github.com/electron/asar) | 1107 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1097 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1093 | `mocha --check-leaks -t 20000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1087 | `webpack && mocha test/unit` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1083 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1081 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1078 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1075 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1075 | `mocha --timeout 30000 --recursive ./tests` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1064 | `standard && mocha -b` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1063 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1059 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1056 | `mocha test --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1054 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1046 | `npm-run-all test:jest test:server:mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [electron/spectron](https://github.com/electron/spectron) | 1045 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1043 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1042 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1036 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1036 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1035 | `mocha test` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1029 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1027 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1024 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1017 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1015 | `mocha --async-only` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1014 | `npm run convertto:es5 && npm run mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1004 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1004 | `mocha --colors ./test/*.spec.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1000 | `mocha --recursive -r tests/setup tests` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 990 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 990 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 981 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 980 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 974 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 974 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 961 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 960 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 953 | `mocha "client.test" --compilers js:babel-register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 951 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 950 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 950 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 949 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 945 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 937 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 937 | `mocha test` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 929 | `mocha spec/*.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 928 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 926 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 920 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 917 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 914 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 917 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 914 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 908 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 902 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 901 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 896 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 895 | `./node_modules/.bin/mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 894 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 891 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 890 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 889 | `nyc --check-coverage mocha test/*.test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 888 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 885 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 879 | `mocha --recursive ./test/*_spec.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 877 | `istanbul cover -- _mocha --reporter spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 876 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 876 | `mocha --reporter list` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 874 | `npm run lint && npm run mocha:no-functional` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 874 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 874 | `standard && standard ./bin/* && mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 873 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 873 | `mocha -t 5000` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 852 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 850 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 848 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 846 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 846 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 845 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 842 | `mocha test/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `nyc mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 836 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 836 | `mocha test` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 836 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 845 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 845 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 842 | `mocha test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 841 | `npm run lint && mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `nyc mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 836 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 836 | `mocha test` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 836 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 834 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 827 | `mocha --exit --use_strict src/*.test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 821 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 820 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 819 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 817 | `mocha --async-only` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 815 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 811 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 809 | `mocha --harmony --full-trace --check-leaks` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 808 | `./node_modules/.bin/mocha test/**/*` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 807 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 806 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 805 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 811 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 809 | `mocha --harmony --full-trace --check-leaks` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 808 | `./node_modules/.bin/mocha test/**/*` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 807 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 806 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 805 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 804 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 802 | `npm run build && istanbul test _mocha test/test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 800 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 800 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 798 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 796 | `mocha --colors --reporter spec test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 796 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 786 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 782 | `mocha -r should --reporter spec test/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 781 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 778 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 778 | `mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 777 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 775 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 775 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 774 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 