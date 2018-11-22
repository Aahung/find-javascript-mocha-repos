# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:20 11/22/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44346 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41690 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41164 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30587 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25081 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24914 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24254 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20757 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19684 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17926 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17511 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17389 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16246 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14542 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14523 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14508 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13645 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13281 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12885 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12604 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12468 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12305 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11997 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11935 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11894 | `mocha --require @babel/register --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 11890 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11105 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10759 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10591 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10539 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10445 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10022 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9866 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9570 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9484 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9268 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9182 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9108 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9072 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8729 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8602 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8516 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8392 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8349 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8516 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8392 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8349 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8345 | `mocha --compilers js:babel-register test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8244 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8164 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7981 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7873 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7657 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7651 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7625 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7623 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7605 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7572 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7517 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7316 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7283 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7199 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7183 | `mocha; jshint *.js lib` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7087 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7043 | `mocha $HARMONY_OPTS` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7017 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6980 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6778 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6591 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6467 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6435 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6327 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6182 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6143 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6131 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6070 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6046 | `mocha` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6023 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5986 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5964 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5950 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5813 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5724 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5602 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5576 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5430 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5414 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5382 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5331 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5236 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5141 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5110 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5079 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5004 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4898 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4875 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4830 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4821 | `mocha --recursive` | 
| [santinic/how2](https://github.com/santinic/how2) | 4805 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4804 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4770 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4756 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4736 | `nyc mocha --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4725 | `mocha --reporter spec -t 8000` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4687 | `npm run lint && npm run mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4673 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4628 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4601 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4497 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4468 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4424 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4406 | `mocha -R spec src` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4395 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4350 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4285 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4271 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4244 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4212 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4204 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4178 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4152 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4151 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4095 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4085 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4049 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4018 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4014 | `NODE_ENV=test mocha --exit` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3936 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3916 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3867 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3867 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3852 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3834 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3798 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3791 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3753 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [primus/primus](https://github.com/primus/primus) | 3743 | `npm run build && mocha test/*.test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3727 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3664 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3620 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3620 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3614 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3610 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3592 | `mocha tests/javascript` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3590 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3568 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3558 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3555 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3510 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3477 | `node_modules/.bin/mocha test/lib/` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3461 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3420 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3393 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3383 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3327 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3297 | `eslint . && mocha -t 5000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3276 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3262 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3252 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3245 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3241 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3236 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3228 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3214 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3191 | `mocha test/index.js && npm run demo` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3183 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3182 | `mocha test/*.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3180 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3166 | `./node_modules/.bin/mocha test/test.*.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3161 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3154 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3143 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3128 | `mocha -R landing test/index` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3124 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3124 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3117 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3107 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3107 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3072 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3041 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3022 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3021 | `eslint . && nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3003 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2981 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2962 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2949 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2940 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2933 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2921 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2913 | `mocha test.js` | 
| [css/csso](https://github.com/css/csso) | 2786 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2780 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2749 | `xo && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2734 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2731 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2726 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2712 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2690 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2674 | `mocha --timeout 100000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2671 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2670 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2665 | `nyc mocha --timeout=10000` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2650 | `mocha "./test/**/*-test.js"` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2646 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2645 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2611 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2586 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2584 | `mocha test/unit --require mochahook` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2808 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [css/csso](https://github.com/css/csso) | 2786 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2780 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2758 | `npm run build && cd test && mocha . --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2749 | `xo && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2734 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2731 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2726 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2712 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2690 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2674 | `mocha --timeout 100000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2671 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2670 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2665 | `nyc mocha --timeout=10000` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2650 | `mocha "./test/**/*-test.js"` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2646 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2645 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2562 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2538 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2532 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2509 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2507 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2494 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2471 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2469 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2431 | `mocha test && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2427 | `mocha --no-colors --reporter spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2424 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2418 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2416 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2410 | `mocha test/index.js --reporter dot` | 
| [pahen/madge](https://github.com/pahen/madge) | 2123 | `npm run lint && npm run mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2081 | `mocha --compilers js:babel-core/register __tests__` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2075 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2017 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2011 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2003 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1997 | `mocha test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1990 | `mocha --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2137 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2136 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2136 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2132 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2129 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2127 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2123 | `npm run lint && npm run mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2113 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2081 | `mocha --compilers js:babel-core/register __tests__` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2075 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2072 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2050 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2028 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2017 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2011 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2003 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1997 | `mocha test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1992 | `mocha --reporter spec --timeout 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1991 | `mocha --require=test/test_helper.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1990 | `mocha --compilers js:babel-register` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1988 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1979 | `npm run mocha && npm run karma` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1949 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1948 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1946 | `mocha --require ./test/common --growl test/expect.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1942 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1937 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1912 | `mocha tests --require @babel/register` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1905 | `mocha --reporter spec && npm run test-typescript` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1896 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1888 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1870 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1866 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1860 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1858 | `mocha --reporter spec --grep .` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1853 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1848 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1839 | `mocha test -u bdd -R spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1813 | `npm run lint && npm run mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1801 | `mocha compiled_tests/` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1763 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1758 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1731 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1720 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1708 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1707 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1691 | `mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1763 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1758 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1731 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1728 | `npm run lint && mocha && npm run typescript` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1726 | `mocha test/setup.js test/spec/*.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1720 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1713 | `mocha test/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1708 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1707 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1698 | `eslint --cache . && tsc && mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1691 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1688 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1684 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1670 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1666 | `mocha && size-limit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1665 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1658 | `nyc mocha --timeout=20000 test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1654 | `mocha spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1646 | `standard "./src/*.js" && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1641 | `mocha --expose-gc --slow 300` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1638 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1637 | `TEST=all mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1637 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1631 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1624 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1620 | `mocha test/test-*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1613 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1612 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1608 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1606 | `mocha --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1591 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1590 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1550 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1549 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1549 | `mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1540 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1532 | `node_modules/.bin/mocha --recursive` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1530 | `NODE_ENV=test mocha tests/*.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1528 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1516 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1532 | `node_modules/.bin/mocha --recursive` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1530 | `NODE_ENV=test mocha tests/*.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1528 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1525 | `mocha -u tdd` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1516 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1500 | `mocha test/unit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1494 | `mocha --check-leaks --require @babel/register` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1494 | `mocha test/**/*.spec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1493 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1490 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1487 | `mocha ./test/test*.js --reporter spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1483 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1478 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1477 | `mocha -R spec` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1436 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1434 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1418 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1415 | `npm run lint && npm run mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1415 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1413 | `mocha --opts test/opts/mocha.opts` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1410 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1407 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1403 | `npm run build && mocha -r should` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1400 | `mocha --reporter dot` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1400 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1387 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1382 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1418 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1415 | `npm run lint && npm run mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1415 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1413 | `mocha --opts test/opts/mocha.opts` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1410 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1407 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1403 | `npm run build && mocha -r should` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1400 | `mocha --reporter dot` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1400 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1387 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1382 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1377 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1370 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1362 | `cross-env NODE_ENV=test nyc mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1360 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1358 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1352 | `npm run prepublishOnly && mocha test/test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1339 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1334 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1321 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1318 | `mocha --check-leaks --reporter spec --bail test/` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1318 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1311 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1311 | `mocha-phantomjs tests/index.html` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1298 | `mocha --compilers js:babel-core/register` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1296 | `mocha test/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1319 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1318 | `mocha --check-leaks --reporter spec --bail test/` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1318 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1311 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1311 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1303 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1302 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1299 | `mocha --timeout 60000 test/` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1298 | `mocha --compilers js:babel-core/register` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1296 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1294 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1282 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1277 | `webpack && npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1276 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1275 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1275 | `mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1273 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1271 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1267 | `npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1265 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1282 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1281 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1277 | `webpack && npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1276 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1275 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1275 | `mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1273 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1271 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1267 | `npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1265 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1263 | `npm run mocha:istanbul` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1259 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1258 | `istanbul test _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1246 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1245 | `npm run lint && mocha --require @babel/register` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1242 | `mocha tests/` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1242 | `mocha --recursive` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1240 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1238 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1236 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1234 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1232 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1229 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1225 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1223 | `mocha --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1218 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1201 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1193 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1193 | `mocha --timeout 20000` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 1168 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1162 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1130 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1125 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1124 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1123 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1122 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1106 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1106 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1101 | `mocha && standard` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1091 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1091 | `standard && mocha -b` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1088 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1072 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1072 | `mocha test/tests.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1071 | `eslint src test && mocha --compilers babel-register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1067 | `mocha --reporter spec test --recursive` | 
| [tomas/needle](https://github.com/tomas/needle) | 1053 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1047 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1036 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1033 | `mocha --reporter spec --timeout 3000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1032 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1066 | `npm run convertto:es5 && npm run mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1067 | `mocha --reporter spec test --recursive` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1054 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1053 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1047 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1045 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1043 | `mocha --async-only` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1036 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1033 | `mocha --reporter spec --timeout 3000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1032 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1066 | `npm run convertto:es5 && npm run mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1067 | `mocha --reporter spec test --recursive` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1054 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1053 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1047 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1045 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1043 | `mocha --async-only` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1036 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1033 | `mocha --reporter spec --timeout 3000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1032 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 997 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 995 | `mocha -R list` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 993 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 991 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 971 | `npm run lint && mocha -R spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 970 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 969 | `mocha --compilers js:babel-register test/*.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 969 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 963 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 954 | `mocha test/*.test.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 950 | `mocha spec/*.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 949 | `mocha --recursive ./test/*_spec.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 947 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 944 | `mocha tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 940 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 940 | `./node_modules/.bin/mocha --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 940 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 940 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 938 | `mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 937 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 936 | `mocha -t 600000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 936 | `./node_modules/.bin/mocha -R spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 930 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 925 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 922 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 921 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 918 | `mocha test --compilers js:babel-register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 912 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 907 | `mocha -t 5000` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 930 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 926 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 925 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 922 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 921 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 920 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 918 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 918 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 917 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 916 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 912 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 892 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 890 | `npm run lint && npm run mocha:no-functional` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 881 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 881 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 874 | `node_modules/.bin/mocha test/spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 874 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 873 | `mocha test` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 870 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 881 | `mocha test/index.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 881 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 881 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 874 | `node_modules/.bin/mocha test/spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 874 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 873 | `mocha test` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 870 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 850 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 846 | `npm run lint && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 845 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 843 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 843 | `npm run build && istanbul test _mocha test/test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 840 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 839 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 835 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 834 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 835 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 834 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 832 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 832 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 832 | `mocha --opts mocha.opts` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 831 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 829 | `mocha --async-only` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 828 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 825 | `mocha -r should --reporter spec test/*.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 824 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 823 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 821 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 817 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 817 | `mocha test` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 791 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 791 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 791 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 789 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 788 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 779 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 778 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 775 | `mocha --recursive -s 15 test/` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 773 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 791 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 789 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 788 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 779 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 778 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 777 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 775 | `mocha --recursive -s 15 test/` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 773 | `npm run lint && mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 769 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 765 | `npm run lint && npm run mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 764 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 761 | `nyc mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 761 | `mocha --harmony tests/**` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 761 | `babel-node node_modules/.bin/_mocha -- test` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 756 | `_mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 756 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 755 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 755 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 753 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 