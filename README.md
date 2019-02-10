# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:24 02/10/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45138 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42323 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42157 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30894 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25743 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25211 | `npm run lint && npm run mocha-node-test` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20153 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18540 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18075 | `mocha` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18540 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18075 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17927 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17489 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15337 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15018 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14716 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14002 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13708 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13236 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13034 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12804 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12795 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12531 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12506 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12355 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12336 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11594 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11262 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11204 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10922 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10842 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10682 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10563 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10438 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9834 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9794 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9711 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9566 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9450 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9444 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9336 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9059 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8929 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8817 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8706 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8607 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8581 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8470 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8362 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8319 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8273 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8167 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8063 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8042 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8018 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7941 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7941 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7882 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7615 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7578 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7532 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7522 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7520 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7233 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7201 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7120 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7060 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6957 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6903 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6591 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6409 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6314 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6284 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6282 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6231 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6221 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6163 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6110 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6040 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5893 | `mocha && eslint lib/**` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5855 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5794 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5785 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5778 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5714 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5650 | `npm run lint && mocha tests/**/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5628 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5602 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5580 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5422 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5411 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5359 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5341 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5132 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5126 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5122 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5081 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5032 | `npm run lint && npm run mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4971 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4969 | `nyc mocha --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4920 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4907 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4890 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4886 | `nyc mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4864 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4857 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4843 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4753 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4678 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4624 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4584 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4561 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4486 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4452 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4421 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4418 | `NODE_ENV=test mocha --exit` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4389 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4385 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4385 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4286 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4238 | `nyc mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4198 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4193 | `mocha -R spec ./test --recursive` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4189 | `npm run build && cd test && mocha . --reporter dot` | 
| [muicss/mui](https://github.com/muicss/mui) | 4142 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4096 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4085 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4019 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4014 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 4019 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4014 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3934 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3921 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3831 | `npm run mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3830 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3823 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3795 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3775 | `mocha && tsc -p ./test/types` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3764 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3489 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3484 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3462 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3451 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3434 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3427 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3401 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3381 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3377 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3376 | `mocha -R landing test/index --exit` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3310 | `mocha test/index.js && npm run demo` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3462 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3451 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3449 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3434 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3427 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3402 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3401 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3381 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3376 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3334 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3326 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3310 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3262 | `mocha test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3065 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3061 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3055 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3024 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3012 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2983 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2970 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2970 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2955 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2926 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2918 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2908 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2902 | `mocha -R spec spec spec/reporters` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3028 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3024 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3012 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3002 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2983 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2970 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2970 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2955 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2926 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2918 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2908 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2905 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2902 | `mocha -R spec spec spec/reporters` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2857 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2846 | `istanbul cover _mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2846 | `istanbul cover _mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2843 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2840 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [css/csso](https://github.com/css/csso) | 2823 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2778 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2768 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2767 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2765 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2760 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2719 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2717 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2715 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2685 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2677 | `mocha test/unit --require mochahook` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2392 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2383 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2322 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2315 | `mocha --compilers js:babel-register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2310 | `npm run lint && npm run mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2298 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2287 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2276 | `mocha test/**/*.coffee` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2383 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2322 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2310 | `npm run lint && npm run mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2298 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2276 | `mocha test/**/*.coffee` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2260 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2255 | `standard && mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2081 | `mocha test/*.test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2075 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2069 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2058 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2053 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2048 | `mocha tests --require @babel/register` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2030 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2025 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2021 | `mocha test/test-*.js` | 
| [then/promise](https://github.com/then/promise) | 2014 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1997 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1976 | `mocha --require ./test/common --growl test/expect.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1970 | `mocha test/**/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1962 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1953 | `bmocha --reporter spec test/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1952 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1942 | `npm run lint && mocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1935 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1923 | `mocha --reporter spec --grep .` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1846 | `npm run lint && npm run mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1832 | `eslint --cache . && tsc && mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1830 | `mocha --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1823 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1814 | `mocha test/setup.js test/spec/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1796 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1781 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1778 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1764 | `npm run lint && mocha && npm run typescript` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1796 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1781 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1778 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1766 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1764 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1752 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1749 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1745 | `mocha ./test/test*.js --reporter spec` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1743 | `mocha test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1752 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1749 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1745 | `mocha ./test/test*.js --reporter spec` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1743 | `mocha test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1738 | `./node_modules/.bin/mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1728 | `mocha test --timeout 600000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1724 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1723 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1723 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1721 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1719 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1716 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1710 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1709 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1703 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1639 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1629 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1627 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1614 | `mocha --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1614 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1612 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1595 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1581 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1580 | `nyc mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1645 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1639 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1629 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1627 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1616 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1614 | `mocha --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1614 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1612 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1595 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1594 | `mocha -R spec ./test/unit/**` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1559 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1550 | `mocha --check-leaks --require @babel/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1542 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1536 | `npm run lint && npm run mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1533 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1528 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1527 | `npm run lint && mocha && karma start --single-run` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1526 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1523 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1516 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1511 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1509 | `mocha test/**/*.spec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1496 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1493 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1489 | `mocha --recursive test` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1484 | `npm run prepublishOnly && mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1482 | `standard && istanbul cover _mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1475 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1473 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1470 | `mocha --opts test/opts/mocha.opts` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1465 | `mocha test --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1454 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1434 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1428 | `npm run build && mocha -r should` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1427 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1426 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/devtron](https://github.com/electron/devtron) | 1417 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1414 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1409 | `istanbul cover _mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1408 | `webpack && npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1276 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1272 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1268 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1267 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1266 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1255 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1255 | `mocha --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1241 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1233 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1227 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1191 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1189 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1189 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1188 | `mocha --reporter spec --bail --check-leaks test/` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1186 | `xo && mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1185 | `mocha --reporter spec --bail --check-leaks test/` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1173 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1076 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1073 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1034 | `mocha --recursive ./test/*_spec.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1030 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1030 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1023 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1010 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1072 | `mocha test` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1070 | `npm run lint && npm run mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1036 | `mocha test/*.test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1034 | `mocha --recursive ./test/*_spec.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1107 | `eslint src test && mocha --compilers babel-register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1106 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1092 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1076 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1073 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 1072 | `mocha test` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1070 | `npm run lint && npm run mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1069 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1003 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1003 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1001 | `./node_modules/.bin/mocha -R spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 998 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 995 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 993 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 988 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 986 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 978 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 976 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 974 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 972 | `mocha -t 600000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 972 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 968 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 967 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 960 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 958 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 953 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 950 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 978 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 976 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 974 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 972 | `mocha -t 600000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 972 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 968 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 967 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 967 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 960 | `nyc mocha specs` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 750 | `mocha 'test/**/*.tests.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 744 | `./node_modules/.bin/mocha tests/*.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 743 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 891 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 888 | `node_modules/.bin/mocha test/spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 888 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 888 | `npm run build && istanbul test _mocha test/test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 886 | `mocha --harmony --full-trace --check-leaks` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 877 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 876 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 871 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 869 | `istanbul cover _mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 868 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 866 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 864 | `mocha --harmony tests/**` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 863 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 862 | `mocha --reporter spec` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 861 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 860 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 859 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 857 | `mocha --reporter spec --bail --check-leaks test/` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 854 | `npm run lint && mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 853 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 852 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [developit/decko](https://github.com/developit/decko) | 852 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 852 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 850 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 848 | `mocha -r babel-register --check-leaks test/index.js` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 848 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 845 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 845 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 840 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 839 | `nyc mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 838 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 836 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 832 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 830 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 826 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 824 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 822 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 821 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 816 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 814 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 814 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 811 | `_mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 809 | `mocha index.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 808 | `mocha test/mocha.js test/crc/index.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 804 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 804 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 801 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 801 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 779 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [koajs/static](https://github.com/koajs/static) | 776 | `mocha --harmony --reporter spec --exit` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 775 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 773 | `mocha ./unittest` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 768 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 768 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 767 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 779 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 779 | `mocha tests --timeout 10000` | 
| [koajs/static](https://github.com/koajs/static) | 776 | `mocha --harmony --reporter spec --exit` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 775 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 773 | `mocha ./unittest` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 768 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 768 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 767 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [susam/texme](https://github.com/susam/texme) | 767 | `standard && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 764 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 763 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 762 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 760 | `./bin/selenium-standalone install && mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 724 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 723 | `mocha` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 721 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [formio/formio](https://github.com/formio/formio) | 714 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 711 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 707 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 706 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 690 | `npm -s run mocha && npm run -s lint` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 684 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 679 | `mocha -R spec` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 676 | `mocha tests/*.test.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 673 | `mocha --require babel-register` | 
| [shime/livedown](https://github.com/shime/livedown) | 671 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 652 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 651 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 647 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 647 | `nyc mocha` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 643 | `mocha -R spec spec/unit spec/integration` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 641 | `nyc mocha test.js` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 641 | `mocha` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 641 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 641 | `mocha test/**.js --timeout 10000` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 639 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 637 | `mocha --reporter spec` | 