# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:01 02/09/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45127 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42313 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42105 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30892 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25730 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25206 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25172 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21472 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20150 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18531 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18072 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17923 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17485 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15330 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15010 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14715 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13998 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12525 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12507 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12354 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11586 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11246 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11201 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10921 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10675 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10557 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10437 | `mocha --harmony` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10675 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10557 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10437 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9830 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9789 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9710 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9562 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9450 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9440 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9334 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9051 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8927 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8810 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8706 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8605 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8580 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8467 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8355 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8320 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8272 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8162 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8062 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8038 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8015 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7940 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7939 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7882 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7613 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7582 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7578 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7524 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7522 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7520 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7449 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7231 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7196 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7120 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7059 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6950 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6902 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6592 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6409 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6313 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6282 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6281 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6231 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6221 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6159 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6111 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6039 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5930 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5893 | `mocha && eslint lib/**` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5826 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5794 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5783 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5771 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5714 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5648 | `npm run lint && mocha tests/**/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5617 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5599 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5579 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5419 | `mocha test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5405 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5356 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5338 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5134 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5126 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5120 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5077 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5031 | `npm run lint && npm run mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4970 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4969 | `nyc mocha --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4920 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4906 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4890 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4877 | `nyc mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4864 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4857 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4841 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4753 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4675 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4611 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4584 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4560 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4486 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4452 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4420 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4414 | `NODE_ENV=test mocha --exit` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4385 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4384 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4384 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4340 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4287 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4238 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4188 | `npm run build && cd test && mocha . --reporter dot` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4179 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4133 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4098 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4095 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4085 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4012 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 4018 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3952 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3933 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3920 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3830 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3823 | `npm run build && mocha test/*.test.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3822 | `npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3794 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3770 | `mocha && tsc -p ./test/types` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3764 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3741 | `mocha test/* --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3729 | `eslint . && mocha -t 5000` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3698 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3674 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3673 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3488 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3482 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3450 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3426 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3425 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3401 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3380 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3376 | `mocha -R landing test/index --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3375 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3309 | `mocha test/index.js && npm run demo` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3496 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3491 | `node_modules/.bin/mocha test/lib/` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3488 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3482 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3450 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3434 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3426 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3425 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3401 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3401 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3380 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3376 | `mocha -R landing test/index --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3375 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3334 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3326 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3185 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3174 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3167 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3116 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3102 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3074 | `npm run mocha && npm run lint` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3063 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3061 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3052 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3027 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3010 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3002 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2981 | `mocha --require @babel/register --recursive spec` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2719 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2715 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2685 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2656 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2635 | `mocha-phantomjs ./test/index.html` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2561 | `mocha test/src/**/*.unit.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2561 | `mocha test --exit && npm run lint` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2556 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2555 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2552 | `TEST=all mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2549 | `mocha test` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2322 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2314 | `mocha --compilers js:babel-register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2309 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2297 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2255 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2220 | `mocha && eslint *.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2208 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2198 | `mocha test/runner.js --reporter spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2504 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2466 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2461 | `mocha -R spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2460 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2453 | `nyc --require babel-register npm run _mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2451 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2450 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2424 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2397 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2392 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2561 | `mocha test/src/**/*.unit.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2561 | `mocha test --exit && npm run lint` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2556 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2556 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2555 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2552 | `TEST=all mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2549 | `mocha test` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2540 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2525 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2504 | `mocha test/index.js --reporter dot` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2503 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 2466 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2461 | `mocha -R spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2460 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2453 | `nyc --require babel-register npm run _mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2451 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1910 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1907 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1892 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1884 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1846 | `npm run lint && npm run mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1830 | `eslint --cache . && tsc && mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1812 | `mocha test/setup.js test/spec/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1796 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1781 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1776 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1766 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1764 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1751 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1749 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1743 | `mocha test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1740 | `mocha ./test/test*.js --reporter spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1708 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1685 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1685 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1665 | `mocha spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1655 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1649 | `NODE_ENV=test mocha tests/*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1638 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1627 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1655 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1649 | `NODE_ENV=test mocha tests/*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1645 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1638 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1627 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1621 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1616 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1614 | `mocha --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1614 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1611 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1607 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1573 | `mocha tests/test-*` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1571 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1550 | `mocha --check-leaks --require @babel/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1536 | `npm run lint && npm run mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1528 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1526 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1516 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1370 | `NODE_PATH=. mocha **/*.spec.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1369 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1366 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1332 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1327 | `mocha spec/exec.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1326 | `mocha test/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1322 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1311 | `npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1306 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1299 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1297 | `mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1474 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1473 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1470 | `mocha --opts test/opts/mocha.opts` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1464 | `mocha test --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1452 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1433 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1428 | `npm run build && mocha -r should` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1425 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1332 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1327 | `mocha spec/exec.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1326 | `mocha test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1325 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1324 | `mocha tests/` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1322 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1321 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1316 | `mocha src/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1312 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1311 | `npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1306 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1302 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1299 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1297 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1369 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1367 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1366 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1362 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1350 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1334 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1332 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1331 | `mocha --timeout 60000 test/` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1327 | `mocha spec/exec.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1326 | `mocha test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1325 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1367 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1366 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1362 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1350 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1334 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1332 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1331 | `mocha --timeout 60000 test/` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1173 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1168 | `mocha --reporter spec test --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1160 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1156 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1149 | `webpack && mocha test/unit` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1140 | `npm run convertto:es5 && npm run mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1139 | `mocha && standard` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1107 | `eslint src test && mocha --compilers babel-register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1106 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1075 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1072 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 1071 | `mocha test` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1070 | `npm run lint && npm run mocha` | 
| [odota/core](https://github.com/odota/core) | 1058 | `NODE_ENV=test mocha --exit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 972 | `mocha -t 600000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 967 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 960 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 954 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 953 | `mocha test --compilers js:babel-register` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 946 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 946 | `./node_modules/.bin/mocha test/**/*` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 940 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1016 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1015 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1013 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1013 | `mocha spec/*.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1011 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1003 | `npm run lint && mocha -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1002 | `mocha --compilers js:babel-register test/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1001 | `./node_modules/.bin/mocha -R spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 998 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 995 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 993 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 988 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 946 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 946 | `./node_modules/.bin/mocha test/**/*` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 940 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 933 | `istanbul cover -- _mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 932 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 967 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 967 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 960 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 957 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 954 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 953 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 949 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 946 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 946 | `./node_modules/.bin/mocha test/**/*` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 940 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 940 | `standard && standard ./bin/* && mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 933 | `istanbul cover -- _mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 932 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 868 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 866 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 863 | `mocha --harmony tests/**` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 862 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 861 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 860 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 859 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 857 | `nyc mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 857 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 853 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 852 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [developit/decko](https://github.com/developit/decko) | 852 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 852 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 850 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 863 | `mocha --harmony tests/**` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 862 | `mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 862 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 861 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 859 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 857 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 853 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 852 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 852 | `npm run lint && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 852 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 850 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 848 | `mocha -r babel-register --check-leaks test/index.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 845 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 809 | `mocha index.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 803 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 801 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 797 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 795 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 792 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 791 | `nyc mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 788 | `eslint . && mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 788 | `eslint . && mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 787 | `jenkins-mocha ./tests/*.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 787 | `mocha --recursive -s 15 test/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 779 | `mocha tests --timeout 10000` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 778 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 774 | `mocha --harmony --reporter spec --exit` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 768 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 768 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 767 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 763 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 762 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 760 | `./bin/selenium-standalone install && mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 750 | `mocha 'test/**/*.tests.js'` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 746 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 745 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 744 | `./node_modules/.bin/mocha tests/*.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 743 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 737 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 736 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 735 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 737 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 736 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 735 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 734 | `mocha ./test/test.js --timeout 1000000` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 732 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 731 | `mocha --reporter spec test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 729 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [electron/apps](https://github.com/electron/apps) | 727 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 721 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 721 | `mocha --reporter spec` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 721 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 717 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [formio/formio](https://github.com/formio/formio) | 714 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 711 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 706 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 702 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 699 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 698 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 697 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 695 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 691 | `./node_modules/.bin/mocha` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 690 | `_mocha -u bdd --colors test/` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 689 | `npm -s run mocha && npm run -s lint` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 703 | `mocha --reporter spec` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 702 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 699 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 698 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 697 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 695 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 691 | `./node_modules/.bin/mocha` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 690 | `_mocha -u bdd --colors test/` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 647 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 641 | `nyc mocha test.js` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 641 | `mocha` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 641 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 640 | `mocha test/**.js --timeout 10000` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 639 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 637 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 637 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 637 | `npm run lint && mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 636 | `mocha --reporter spec` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 636 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 635 | `node_modules/.bin/mocha test` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 634 | `mocha test` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 632 | `mocha --ui bdd --reporter spec test/` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 630 | `istanbul cover _mocha && eslint .` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 603 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [wclimb/Koa2-blog](https://github.com/wclimb/Koa2-blog) | 601 | `./node_modules/mocha/bin/mocha --harmony test` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 598 | `mocha` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 598 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 594 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 591 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 590 | `mocha test/test.js --reporter spec` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 589 | `mocha build/test` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 588 | `mocha --compilers js:./babel-register` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 586 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [opencomponents/oc](https://github.com/opencomponents/oc) | 585 | `npm run build && node tasks/mochaTest.js` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 643 | `mocha -R spec spec/unit spec/integration` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 641 | `nyc mocha test.js` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 641 | `mocha` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 641 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 640 | `mocha test/**.js --timeout 10000` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 639 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 637 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 637 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 637 | `npm run lint && mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 636 | `mocha --reporter spec` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 636 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 635 | `node_modules/.bin/mocha test` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 632 | `mocha --ui bdd --reporter spec test/` | 