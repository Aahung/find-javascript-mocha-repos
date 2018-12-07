# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:32 12/07/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44527 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41770 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41380 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30651 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24996 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24450 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20949 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19783 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18055 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17631 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17488 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16474 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14718 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14585 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14583 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13721 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13374 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12908 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12653 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12549 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12323 | `mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12312 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12074 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12067 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12006 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11203 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10872 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10688 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10679 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10474 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10446 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10319 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10308 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10151 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9606 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9546 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9391 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9374 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9204 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9171 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9159 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8767 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8622 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8529 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8409 | `grunt clean:test && mocha --exit` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8387 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8373 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8352 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8190 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7998 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7904 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7761 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7754 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7704 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7691 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7686 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7581 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7542 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7458 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7374 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7275 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7267 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7253 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7136 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7062 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7011 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6835 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6653 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6569 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6470 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6335 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6304 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6175 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6163 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6081 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6074 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6024 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6014 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5998 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5824 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5796 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5617 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5617 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5498 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5417 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5411 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5386 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5264 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5249 | `mocha -r esm` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5199 | `mocha src/**/*Tests.js --harmony` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5173 | `mocha test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5138 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5089 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5080 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4901 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4900 | `gulp build; mocha;` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4872 | `mocha --recursive` | 
| [teambit/bit](https://github.com/teambit/bit) | 4852 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4844 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4817 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4811 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4806 | `./node_modules/.bin/mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4782 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4781 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4734 | `npm run lint && npm run mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4728 | `mocha --reporter spec -t 8000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4683 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4656 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4572 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4516 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4509 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4486 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4472 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4451 | `mocha -R spec src` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4382 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4356 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4311 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4265 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4218 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4218 | `nyc mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4194 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4184 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4107 | `NODE_ENV=test mocha --exit` | 
| [muicss/mui](https://github.com/muicss/mui) | 4100 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4092 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4062 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4037 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3966 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3922 | `export TESTING=true; mocha --reporter list` | 
| [expressjs/session](https://github.com/expressjs/session) | 3868 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3805 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3804 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3767 | `NODE_ENV=test mocha test/**/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3763 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3693 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3669 | `mocha test/* --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3660 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3632 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3625 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3618 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3594 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3541 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3505 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3460 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3459 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3407 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3396 | `eslint . && mocha -t 5000` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3391 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3352 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3214 | `mocha test/index.js && npm run demo` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3190 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3172 | `./node_modules/.bin/mocha test/test.*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3159 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3147 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3145 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3124 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3122 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3047 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3047 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3038 | `eslint . && nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3023 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3190 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3172 | `./node_modules/.bin/mocha test/test.*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3168 | `mocha -R landing test/index --exit` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3159 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3159 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3147 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3145 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3124 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3122 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3047 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3047 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3038 | `eslint . && nyc mocha --recursive` | 
| [mde/ejs](https://github.com/mde/ejs) | 3029 | `mocha --require should --reporter spec` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3023 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2976 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2965 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2953 | `mocha test.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2951 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2940 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2937 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2931 | `node_modules/.bin/mocha --reporter spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2917 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2916 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2907 | `mocha test-node` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2905 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2903 | `mocha --require @babel/register --recursive spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2902 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2899 | `mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2899 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2866 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2864 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2831 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2824 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2791 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2779 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2777 | `npm run build && cd test && mocha . --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2752 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2750 | `xo && mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2742 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2740 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2730 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2722 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2702 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2684 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2684 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2682 | `nyc mocha --timeout=10000` | 
| [retejs/rete](https://github.com/retejs/rete) | 2682 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2676 | `mocha --timeout 100000` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2665 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2318 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2317 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2299 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2292 | `nyc --require babel-register npm run _mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2291 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2254 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2234 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2208 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2201 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2174 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2173 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1692 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1665 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1658 | `standard "./src/*.js" && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1656 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1649 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1646 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1639 | `mocha test/test-*.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1609 | `mocha --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1592 | `mocha test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2081 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2075 | `./node_modules/.bin/mocha && npm run jshint` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2036 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2024 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2020 | `mocha --compilers js:babel-register` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2006 | `npm run lint && mocha -R dot && npm run cover` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2006 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2000 | `mocha --reporter spec --timeout 5000` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1993 | `npm run mocha && npm run karma` | 
| [then/promise](https://github.com/then/promise) | 1976 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1975 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1953 | `mocha --bail --reporter spec --check-leaks test/` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1951 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1949 | `mocha --require ./test/common --growl test/expect.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1943 | `mocha && npm run lint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1941 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1931 | `mocha tests --require @babel/register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1914 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1906 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1904 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1891 | `mocha test/**/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1888 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1884 | `npm run lint && mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1872 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1868 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1861 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1850 | `mocha test -u bdd -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1848 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1825 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1825 | `mocha compiled_tests/` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1824 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1821 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1799 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1793 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1769 | `npm run lint && npm run mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1765 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1758 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1748 | `mocha test/setup.js test/spec/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1733 | `npm run lint && mocha && npm run typescript` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1711 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1706 | `mocha tests.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1695 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1693 | `nyc mocha --timeout=20000 test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1692 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1689 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1679 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1671 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1665 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1658 | `standard "./src/*.js" && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1656 | `mocha spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1243 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1230 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1215 | `mocha --timeout 20000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1165 | `mocha --recursive -r tests/setup tests` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1136 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1124 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1620 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1611 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1609 | `mocha --reporter spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1598 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1595 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1592 | `mocha test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1575 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1462 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1461 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1456 | `mocha test/tests.js --timeout=10000` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1455 | `npm run lint && mocha && karma start --single-run` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1441 | `npm run lint && npm run mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1428 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1422 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1412 | `npm run build && mocha -r should` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1408 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1266 | `npm run lint && mocha --require @babel/register` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1264 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1263 | `istanbul test _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [router5/router5](https://github.com/router5/router5) | 1249 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1248 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1248 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1243 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1232 | `mocha --timeout 30000 --recursive ./tests` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1214 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1207 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1428 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1424 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1422 | `mocha --opts test/opts/mocha.opts` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1422 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1420 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1412 | `npm run build && mocha -r should` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1408 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1392 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1385 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1381 | `mocha --recursive` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1380 | `mocha --recursive test/bin` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1377 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1392 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1385 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1381 | `mocha --recursive` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1380 | `mocha --recursive test/bin` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1377 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1374 | `npm run prepublishOnly && mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1367 | `mocha --recursive test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1365 | `cross-env NODE_ENV=test nyc mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1365 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1364 | `./node_modules/.bin/mocha test` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1363 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1355 | `mocha test --compilers js:babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1347 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1347 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1340 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1339 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1338 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1330 | `mocha --check-leaks --reporter spec --bail test/` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1322 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1313 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1312 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1313 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1312 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1310 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1308 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1304 | `mocha --timeout 60000 test/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1302 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1302 | `mocha test/*.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1301 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1298 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1297 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1288 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1283 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1283 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1283 | `npm run mocha:istanbul` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1282 | `mocha src/test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1277 | `mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1249 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1232 | `mocha --timeout 30000 --recursive ./tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1230 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1215 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1214 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1207 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1206 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1232 | `mocha --timeout 30000 --recursive ./tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1230 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1230 | `mocha --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1215 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1214 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1207 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1206 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 1178 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1176 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1168 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1165 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1165 | `mocha --recursive -r tests/setup tests` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1161 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1160 | `mocha $(find test -name '*.test.js') --exit` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1141 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1136 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1134 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1131 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1125 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1122 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1116 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1112 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1112 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1104 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1032 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1025 | `mocha --recursive test/unit/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1023 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 999 | `mocha -R list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 996 | `mocha --reporter spec --bail --check-leaks test/` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 994 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 994 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 988 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1042 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1039 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1038 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1032 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1025 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1038 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1032 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1025 | `mocha --recursive test/unit/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1023 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1023 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 999 | `mocha -R list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 996 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 996 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 994 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 994 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 988 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 979 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 978 | `npm run lint && mocha -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 976 | `mocha --compilers js:babel-register test/*.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 976 | `mocha test/*.test.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 973 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 969 | `mocha "client.test" --compilers js:babel-register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 968 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 968 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 966 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 965 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 961 | `mocha --recursive ./test/*_spec.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 961 | `mocha spec/*.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 958 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 952 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 951 | `./node_modules/.bin/mocha --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 950 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 949 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 946 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 943 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 943 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 941 | `mocha -t 600000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 941 | `mocha test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 935 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 929 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 928 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 927 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 926 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 925 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 922 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 919 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 918 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 918 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 916 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 912 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 910 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 918 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 918 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 916 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 913 | `npm run lint && npm run mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 912 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 910 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 908 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 907 | `standard && standard ./bin/* && mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 903 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 901 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 899 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 887 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 884 | `mocha --timeout 200000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 879 | `node_modules/.bin/mocha test/spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 876 | `./node_modules/.bin/mocha test/**/*` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 874 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 871 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 871 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 861 | `mocha --reporter list` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 858 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 856 | `istanbul cover _mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 855 | `npm run build && istanbul test _mocha test/test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 851 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 850 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 850 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 850 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 849 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 844 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 839 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 838 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 836 | `mocha -r should --exit test/*.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 836 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 835 | `mocha --opts mocha.opts` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 834 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 833 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 831 | `mocha --async-only` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 829 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 829 | `mocha && ember test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 826 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 806 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 804 | `./node_modules/.bin/mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 803 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 799 | `_mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 797 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 794 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 793 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 791 | `mocha --no-timeouts` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 806 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 804 | `./node_modules/.bin/mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 803 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 799 | `_mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 797 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 794 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 793 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 744 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [koajs/static](https://github.com/koajs/static) | 743 | `mocha --harmony --reporter spec --exit` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 741 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 740 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 740 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 734 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 731 | `npm run test-mocha && npm run test-karma` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 731 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 729 | `mocha` | 