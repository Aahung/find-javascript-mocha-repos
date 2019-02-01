# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:34 02/01/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45076 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42169 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42060 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30868 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25920 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25625 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25191 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25125 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21415 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20118 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18497 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18033 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17876 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17370 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15270 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14973 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14708 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13962 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13681 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13167 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13015 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12787 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12785 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12482 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12453 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12357 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12299 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11541 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11175 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11174 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10904 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10642 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10507 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10426 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9778 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9771 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9708 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9537 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9443 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9406 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9324 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8946 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8913 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8753 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8692 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8596 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8574 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8458 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8330 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8272 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8263 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8111 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8054 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8021 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7975 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7917 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7913 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7877 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7601 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7585 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7548 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7503 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7494 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7494 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7193 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7174 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7112 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7040 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6898 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6875 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6577 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6400 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6287 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6278 | `mocha tests/node.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6249 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6219 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6210 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6135 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6103 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6012 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5703 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5622 | `npm run lint && mocha tests/**/*.js` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5570 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5566 | `mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 5541 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5405 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5392 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5343 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5308 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5208 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5124 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5308 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5208 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5124 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5083 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5057 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4961 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4956 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4941 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4936 | `npm run lint && npm run mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4917 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4895 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4886 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4860 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4850 | `mocha test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4843 | `nyc mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4837 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4750 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4653 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4589 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4584 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4556 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4484 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4441 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4384 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4381 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4370 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4364 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4362 | `NODE_ENV=test mocha --exit` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4321 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4280 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4236 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4194 | `mocha -R spec ./test --recursive` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4143 | `npm run build && cd test && mocha . --reporter dot` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4127 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4093 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4093 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4069 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4001 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3992 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3945 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3930 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3905 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3831 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3820 | `npm run build && mocha test/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 3813 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3783 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3755 | `npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3546 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3490 | `node_modules/.bin/mocha test/lib/` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3483 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3446 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3425 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3414 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3395 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3388 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3366 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3328 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3313 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3307 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3371 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3370 | `mocha -R landing test/index --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3366 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3328 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3313 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3307 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3256 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3236 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3226 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3224 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3206 | `mocha --require should --reporter spec` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3184 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3171 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3163 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3161 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3160 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2252 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2246 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2208 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2195 | `mocha test/runner.js --reporter spec` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2156 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2109 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2548 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2539 | `mocha test/src/**/*.unit.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2536 | `mocha && eslint .` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2533 | `TEST=all mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2497 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2495 | `mocha test/index.js --reporter dot` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2460 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2453 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [noble/noble](https://github.com/noble/noble) | 2410 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2392 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2383 | `grunt jshint && mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2757 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2755 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2717 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2713 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2688 | `mocha --timeout 100000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2674 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2648 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2633 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2601 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2717 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2714 | `mocha --recursive --watch` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2713 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2688 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2679 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2674 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2648 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2633 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2601 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1887 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1880 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1843 | `npm run lint && npm run mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1814 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1774 | `mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1767 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1746 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2312 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2291 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2289 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2286 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2252 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2246 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2242 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2227 | `mocha test/**/*.coffee` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2225 | `npm run lint && mocha tests/**/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2210 | `mocha && eslint *.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2187 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2186 | `cross-env BABEL_ENV=test mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2183 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2156 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2150 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2146 | `mocha --compilers js:babel-register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2137 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2134 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2133 | `mocha --compilers js:babel-core/register __tests__` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2109 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 2072 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2056 | `npm run mocha && npm run karma` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2048 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2044 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2040 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2031 | `mocha && npm run lint` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2022 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2021 | `mocha --reporter spec --timeout 5000` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2016 | `mocha test` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1971 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1965 | `mocha test/**/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1957 | `mocha --reporter spec && npm run test-typescript` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1952 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1950 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1950 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1933 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1932 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1918 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1915 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1904 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1899 | `mocha compiled_tests/` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1767 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1762 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1759 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1746 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1741 | `mocha test/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1713 | `mocha --check-leaks --reporter spec --bail` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1713 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1814 | `npm run lint && npm run mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1808 | `eslint --cache . && tsc && mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1806 | `mocha test/setup.js test/spec/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1774 | `mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1767 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1762 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1759 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1746 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1746 | `mocha test/test-*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1745 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1615 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1613 | `./node_modules/mocha/bin/mocha -R spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1609 | `mocha --recursive` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1587 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1576 | `nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1573 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1563 | `mocha tests/test-*` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1655 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1652 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1640 | `NODE_ENV=test mocha tests/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1638 | `mocha tests/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1635 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1628 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1626 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1615 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1614 | `mocha test.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1610 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1609 | `mocha --recursive` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1615 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1614 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1613 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1610 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1609 | `mocha --recursive` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1587 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1577 | `mocha -R spec ./test/unit/**` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1576 | `nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1573 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1327 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1327 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1323 | `mocha test/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1319 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1319 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1314 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1309 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1302 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1302 | `mocha --timeout 30000 --recursive ./tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1299 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1297 | `mocha --timeout 20000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1292 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1292 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1285 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1501 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1494 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1482 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1478 | `mocha --recursive test` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1473 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1471 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1471 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1470 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1469 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1468 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1468 | `npm run prepublishOnly && mocha test/test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1431 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1423 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1421 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/devtron](https://github.com/electron/devtron) | 1413 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1410 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1397 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1392 | `mocha --check-leaks --reporter spec --bail test/` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1389 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1388 | `webpack && npm run lint && npm run mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1376 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1371 | `npm run mocha:istanbul` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1360 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1359 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1353 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1349 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1327 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1327 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1323 | `mocha test/*.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1323 | `mocha tests/` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1319 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1319 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1315 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1314 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1313 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1310 | `npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1309 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1302 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1302 | `mocha --timeout 30000 --recursive ./tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1299 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1297 | `mocha --timeout 20000` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1296 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [variety/variety](https://github.com/variety/variety) | 1274 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1267 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1266 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1254 | `mocha --reporter spec` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1253 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [electron/asar](https://github.com/electron/asar) | 1230 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1225 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1198 | `mocha --recursive -r tests/setup tests` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1185 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1183 | `mocha --reporter spec --bail --check-leaks test/` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1182 | `xo && mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1181 | `mocha --reporter spec --bail --check-leaks test/` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1177 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1177 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1167 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1156 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1146 | `webpack && mocha test/unit` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1134 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1132 | `mocha && standard` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1129 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1169 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1168 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1167 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1162 | `mocha test` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1157 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1156 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1146 | `webpack && mocha test/unit` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1134 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1095 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1086 | `mocha test/tests.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1034 | `mocha test/*.test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1032 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1028 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1025 | `mocha --reporter spec --bail --check-leaks test/` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1022 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1020 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1016 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1014 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1011 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1011 | `mocha spec/*.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1006 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1001 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1000 | `npm run lint && mocha -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1001 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1000 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 995 | `./node_modules/.bin/mocha -R spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 985 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 982 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 982 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 981 | `mocha "client.test" --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 975 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 972 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 966 | `mocha -t 600000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 966 | `mocha -t 600000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 965 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 965 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 964 | `mocha tests` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 963 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 962 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 960 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 952 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 951 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 948 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 948 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 945 | `./node_modules/.bin/mocha test/**/*` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 944 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 941 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 937 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 931 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 930 | `standard && standard ./bin/* && mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 928 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 927 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 927 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 919 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 917 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 917 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 913 | `mocha test/index.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 911 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 910 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 909 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 908 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 888 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 886 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 885 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 884 | `mocha --harmony --full-trace --check-leaks` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 880 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 877 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 875 | `mocha --reporter list` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 867 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 864 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 849 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 849 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 847 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 845 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 845 | `npm run lint && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 843 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 843 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 841 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 832 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 828 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 828 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 824 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 823 | `npm run mocha-test test/integration` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 823 | `_mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 849 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 849 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 847 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 845 | `npm run lint && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 843 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 843 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 841 | `mocha -r babel-register --check-leaks test/index.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 841 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 834 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 832 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 834 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 832 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 828 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 824 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 823 | `npm run mocha-test test/integration` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 823 | `_mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 821 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 817 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 817 | `mocha --colors --reporter spec test.js` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 781 | `eslint . && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 775 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 774 | `jenkins-mocha ./tests/*.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 773 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 771 | `mocha --harmony --reporter spec --exit` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 767 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 766 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 765 | `npm run-script jshint && npm run-script mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 762 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 773 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 771 | `mocha --harmony --reporter spec --exit` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 767 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 766 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 765 | `npm run-script jshint && npm run-script mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 762 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 760 | `mocha --reporter spec build/test/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 759 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 759 | `./bin/selenium-standalone install && mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 794 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 793 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 793 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 791 | `mocha tests --timeout 10000` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 790 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 789 | `npm run lint && npm run mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 785 | `mocha test` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 783 | `mocha --recursive -s 15 test/` | 