# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:10 12/31/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44753 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41900 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41692 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30757 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25084 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24728 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21170 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19939 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18237 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17808 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17655 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16819 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14957 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14766 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14636 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13814 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13491 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12954 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12733 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12702 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12674 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12350 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12233 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12173 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12167 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11344 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10999 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10865 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10771 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10638 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9657 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9639 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9560 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9408 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9397 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9274 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9241 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8820 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8701 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8651 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8543 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8517 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8491 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8430 | `grunt clean:test && mocha --exit` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8222 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8651 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8543 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8517 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8491 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8430 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8366 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8222 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8013 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7954 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7916 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7893 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7786 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7779 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7765 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7584 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7572 | `npm run build && istanbul cover _mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7510 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7458 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7437 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7382 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7363 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7307 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7089 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7066 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6927 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6746 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6677 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6506 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6479 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6366 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6235 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6190 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6168 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6127 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6095 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6072 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6062 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6055 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5877 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5853 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5676 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5643 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5590 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5579 | `npm run lint && mocha tests/**/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5514 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5455 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5444 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5308 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5293 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5254 | `mocha test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5204 | `mocha src/**/*Tests.js --harmony` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5161 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [teambit/bit](https://github.com/teambit/bit) | 5134 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5104 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4965 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4917 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4905 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4860 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4847 | `./node_modules/.bin/mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4846 | `nyc mocha --exit` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4836 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4833 | `mocha test` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4831 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4810 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4785 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4779 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4735 | `mocha --reporter spec -t 8000` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4732 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4574 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4538 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4509 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4508 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4467 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4367 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4364 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4224 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4210 | `NODE_ENV=test mocha --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4199 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4127 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4074 | `mocha --require should --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3951 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3923 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3862 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3637 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3628 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3604 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3599 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3582 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3539 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3486 | `node_modules/.bin/mocha test/lib/` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3466 | `mocha && tsc -p ./test/types` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3452 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3378 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3376 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3301 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3282 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3279 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3259 | `mocha test/index.js && npm run demo` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3486 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3452 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3415 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3378 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3376 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3369 | `npm run mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3346 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3328 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3301 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3282 | `mocha` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3426 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3416 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3415 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3378 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3376 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3369 | `npm run mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3346 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3345 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3328 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3304 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3301 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3282 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3282 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3279 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3276 | `mocha -R landing test/index --exit` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3259 | `mocha test/index.js && npm run demo` | 
| [mde/ejs](https://github.com/mde/ejs) | 3089 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3078 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3063 | `npm run lint && nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3053 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2993 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2970 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2969 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2966 | `node_modules/.bin/mocha --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2949 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2947 | `mocha -R spec --recursive src/test` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2942 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2940 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2937 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2930 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2930 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2928 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2907 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2887 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3007 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2993 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2970 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2969 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2966 | `node_modules/.bin/mocha --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2949 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2947 | `mocha -R spec --recursive src/test` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2942 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2940 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2937 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2930 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2930 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2928 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2907 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2887 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2877 | `mocha -R spec spec spec/reporters` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2876 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [retejs/rete](https://github.com/retejs/rete) | 2725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2721 | `mocha "./test/**/*-test.js"` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2696 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2695 | `nyc mocha --timeout=10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2681 | `mocha --timeout 100000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2678 | `nyc mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2646 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2639 | `mocha test/unit --require mochahook` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2631 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2605 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2571 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2509 | `mocha --reporter=spec test/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2509 | `mocha test --exit && npm run lint` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2503 | `nyc --reporter=html --reporter=text mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2481 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2475 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2453 | `mocha test/index.js --reporter dot` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2444 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2437 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2436 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2425 | `mocha -R spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2404 | `TEST=all mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2379 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [noble/noble](https://github.com/noble/noble) | 2375 | `mocha -R spec test/*.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2368 | `nyc --require babel-register npm run _mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2367 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2524 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2509 | `mocha --reporter=spec test/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2509 | `mocha test --exit && npm run lint` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2503 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2493 | `mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2481 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2475 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2453 | `mocha test/index.js --reporter dot` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2444 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2437 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2436 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2425 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2409 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2404 | `TEST=all mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2299 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gajus/swing](https://github.com/gajus/swing) | 2294 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2240 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2222 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2219 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2214 | `npm run lint && npm run mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2211 | `npm run lint && mocha tests/**/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2193 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2180 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2179 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2170 | `mocha test/runner.js --reporter spec` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2167 | `mocha && eslint *.js` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2164 | `mocha test/**/*.coffee` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2156 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2145 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2139 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2131 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2118 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2112 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2102 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2085 | `mocha --compilers js:babel-register` | 
| [then/promise](https://github.com/then/promise) | 1996 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1967 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1958 | `mocha --require ./test/common --growl test/expect.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1938 | `mocha test` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1932 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1871 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1854 | `mocha compiled_tests/` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1852 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1836 | `npm run lint && npm run mocha` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1980 | `mocha && npm run lint` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1967 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1958 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1957 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1945 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1938 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1936 | `mocha --reporter spec && npm run test-typescript` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1932 | `mocha test/**/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1929 | `bmocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1921 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1891 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1885 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1871 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1870 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1854 | `mocha compiled_tests/` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1852 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1844 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1836 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1660 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1631 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1617 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1617 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1612 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1610 | `mocha ./test/test*.js --reporter spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1603 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1603 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1677 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1675 | `mocha && size-limit` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1675 | `mocha test/test-*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1668 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1667 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1660 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1631 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1617 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1612 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1610 | `mocha ./test/test*.js --reporter spec` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1678 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1677 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1675 | `mocha && size-limit` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1675 | `mocha test/test-*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1668 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1667 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1660 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1539 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1535 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1529 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1522 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1519 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1518 | `mocha -R spec ./test/unit/**` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1516 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1511 | `mocha tests/test-*` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1509 | `mocha --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1507 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1506 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1503 | `mocha test/**/*.spec.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1491 | `mocha --timeout 10000 ./tests/lib.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1489 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1572 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1563 | `nyc mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1558 | `mocha test/unit` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1539 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1535 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1529 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1459 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1447 | `standard && istanbul cover _mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1446 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1440 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1440 | `mocha --opts test/opts/mocha.opts` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1437 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1423 | `npm run prepublishOnly && mocha test/test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1415 | `npm run build && mocha -r should` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1408 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1404 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1398 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1398 | `mocha --recursive test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1391 | `mocha --recursive test/bin` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1382 | `mocha test --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1378 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1378 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1371 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1370 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1361 | `NODE_PATH=. mocha **/*.spec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1328 | `lerna run test && mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1322 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1321 | `webpack && npm run lint && npm run mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1316 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1313 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1308 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1301 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1301 | `npm run lint && mocha --require @babel/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1299 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1289 | `npm run lint && npm run mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1287 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1279 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1278 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1263 | `mocha --timeout 30000 --recursive ./tests` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1301 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1301 | `npm run lint && mocha --require @babel/register` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1299 | `mocha src/test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1299 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1289 | `npm run lint && npm run mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1287 | `mocha tests/` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1286 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1284 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1280 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1279 | `istanbul test _mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1267 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1267 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1264 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1263 | `mocha --timeout 30000 --recursive ./tests` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1220 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1210 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1204 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1193 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1174 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1171 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1170 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1164 | `mocha $(find test -name '*.test.js') --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1160 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1159 | `npm-run-all test:jest test:server:mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1157 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1156 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1150 | `istanbul cover _mocha test/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1147 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1141 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1138 | `webpack && mocha test/unit` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1126 | `mocha test/*` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1150 | `istanbul cover _mocha test/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1141 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1138 | `webpack && mocha test/unit` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1129 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1114 | `mocha && standard` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1112 | `mocha --reporter spec test --recursive` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1112 | `standard && mocha -b` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1111 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1157 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1156 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1150 | `istanbul cover _mocha test/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1147 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1141 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1138 | `webpack && mocha test/unit` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1129 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1126 | `mocha test/*` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1087 | `mocha --compilers js:babel-register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1084 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1082 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1062 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1057 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1053 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1015 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1013 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1007 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1000 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 998 | `mocha test/*.test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 988 | `npm run lint && mocha -R spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 982 | `mocha --compilers js:babel-register test/*.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 982 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 981 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 981 | `mocha spec/*.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 977 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 977 | `npm run lint && npm run mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 976 | `./node_modules/.bin/mocha -R spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 990 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 988 | `npm run lint && mocha -R spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 982 | `mocha --compilers js:babel-register test/*.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 982 | `mocha --recursive ./test/*_spec.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 981 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 981 | `mocha spec/*.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 980 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 977 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 977 | `npm run lint && npm run mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 976 | `./node_modules/.bin/mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 975 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 975 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 975 | `mocha "client.test" --compilers js:babel-register` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 971 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 967 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 963 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 959 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 956 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 956 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 955 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 953 | `mocha -t 600000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 951 | `mocha tests` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 946 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 946 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 938 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 938 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 938 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 938 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 936 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 936 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 935 | `nyc mocha specs` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 935 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 934 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 933 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 928 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 927 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 923 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 920 | `istanbul cover -- _mocha --reporter spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 904 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 903 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 902 | `mocha test` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 894 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 890 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 880 | `node_modules/.bin/mocha test/spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 890 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 880 | `node_modules/.bin/mocha test/spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 876 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 872 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 869 | `npm run build && istanbul test _mocha test/test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 867 | `mocha --reporter list` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 844 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 842 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 841 | `mocha --opts mocha.opts` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 837 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 837 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 837 | `mocha --async-only` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 835 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 833 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 831 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 831 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 853 | `mocha --check-leaks -t 20000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 851 | `mocha -r should --exit test/*.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 851 | `mocha --reporter spec --bail --check-leaks test/` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 844 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 844 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 843 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 842 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 841 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 838 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 837 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 837 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 837 | `mocha --async-only` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 797 | `_mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 791 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 785 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 785 | `npm run lint && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 791 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 785 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 785 | `mocha test` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 785 | `npm run lint && npm run mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 782 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 780 | `mocha index.test.js` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 779 | `mocha test/mocha.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 778 | `mocha --recursive -s 15 test/` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 778 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 684 | `mocha test/**/test_*.js` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 683 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 681 | `./node_modules/.bin/mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 679 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 679 | `mocha --bail test/` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 678 | `mocha -R spec` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 672 | `_mocha -u bdd --colors test/` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 667 | `mocha --require babel-register` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 665 | `npm -s run mocha && npm run -s lint` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 767 | `mocha tests --timeout 10000` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 763 | `mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 762 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 762 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 762 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 760 | `standard && mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 756 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 756 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 755 | `mocha --harmony --reporter spec --exit` | 