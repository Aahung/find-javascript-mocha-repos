# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:25 01/10/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44840 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41950 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41836 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30784 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25122 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24848 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21244 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20004 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18321 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17888 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17698 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16972 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15063 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14833 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14660 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13859 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13547 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12970 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12838 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12729 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12706 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12353 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12318 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12264 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12202 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11407 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11051 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10960 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10812 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10540 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10399 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10333 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9680 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9678 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9630 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9459 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9410 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9332 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9261 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8859 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8765 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8670 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8597 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8547 | `mocha --check-leaks -R dot` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8535 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8441 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8349 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8232 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8030 | `npm run eslint && npm run mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8025 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7974 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7971 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7839 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7816 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7809 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7597 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7580 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7474 | `mocha --compilers js:babel-core/register` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7457 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7415 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7396 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7363 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7102 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7095 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6962 | `npm run jshint && mocha test/` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6931 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6762 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6734 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6532 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6379 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6252 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6210 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6190 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6157 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6143 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6076 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6072 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6072 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5911 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5866 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5710 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5660 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5639 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5591 | `npm run lint && mocha tests/**/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5590 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5498 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5457 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5332 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5313 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5297 | `mocha test` | 
| [teambit/bit](https://github.com/teambit/bit) | 5234 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5211 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5205 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5111 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4997 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4931 | `gulp build; mocha;` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4913 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4910 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4886 | `nyc mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4869 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4860 | `./node_modules/.bin/mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4854 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4845 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4836 | `mocha test` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4834 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4819 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4818 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4760 | `nyc mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4253 | `NODE_ENV=test mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4229 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4197 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4100 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4079 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4079 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4023 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3987 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3945 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3929 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3895 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3817 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3802 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3735 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3699 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3647 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3638 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3628 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3609 | `eslint . && mocha -t 5000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3588 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3609 | `eslint . && mocha -t 5000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3588 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3585 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3556 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3511 | `nyc mocha && tsc` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3494 | `npm run mocha` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3487 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3429 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3418 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3412 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3187 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3177 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3162 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3140 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [mde/ejs](https://github.com/mde/ejs) | 3135 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3108 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3067 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3058 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3026 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3001 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2986 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2983 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2962 | `mocha test-node` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2956 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2952 | `mocha -R spec --recursive src/test` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2945 | `mocha --require @babel/register --recursive spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2934 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2910 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2898 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2898 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2849 | `npm run build && cd test && mocha . --reporter dot` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2843 | `istanbul cover _mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2794 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2783 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2755 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2742 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2741 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2707 | `mocha --recursive --watch` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2898 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2884 | `mocha -R spec spec spec/reporters` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2862 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2849 | `npm run build && cd test && mocha . --reporter dot` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2843 | `istanbul cover _mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2835 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [css/csso](https://github.com/css/csso) | 2807 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2794 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2783 | `mocha --require should --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2773 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2758 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2742 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2741 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [tj/should.js](https://github.com/tj/should.js) | 2730 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2730 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2725 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2755 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2742 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2741 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [tj/should.js](https://github.com/tj/should.js) | 2730 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2730 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2725 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2707 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2698 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2687 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2685 | `mocha --timeout 100000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2651 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2649 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2633 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2611 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2576 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2540 | `mocha test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2528 | `mocha test --exit && npm run lint` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2527 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2509 | `mocha --reporter=spec test/*-test.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2508 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2498 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2485 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2473 | `mocha test/index.js --reporter dot` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2460 | `TEST=all mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2447 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2445 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2434 | `mocha -R spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2427 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 2418 | `mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2197 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2183 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2179 | `mocha test/runner.js --reporter spec` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2147 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2104 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2071 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2241 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2233 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [pahen/madge](https://github.com/pahen/madge) | 2233 | `npm run lint && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2216 | `npm run lint && mocha tests/**/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2200 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2197 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2183 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2179 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2173 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2170 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2147 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2143 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2241 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2233 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [pahen/madge](https://github.com/pahen/madge) | 2233 | `npm run lint && npm run mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2229 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2216 | `npm run lint && mocha tests/**/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2200 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2197 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2183 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2179 | `mocha test/runner.js --reporter spec` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2174 | `mocha && eslint *.js` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2173 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2170 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2147 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2143 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2134 | `./node_modules/.bin/mocha && npm run jshint` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2125 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2117 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2104 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2071 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 2042 | `mocha test/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2041 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2033 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2023 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2017 | `mocha tests --require @babel/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2015 | `mocha --reporter spec --timeout 5000` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2014 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2010 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2003 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1998 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1971 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1962 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1960 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1957 | `mocha --bail --reporter spec --check-leaks test/` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1950 | `mocha test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1945 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1804 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1797 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1784 | `nyc mocha --timeout=20000 test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1744 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1743 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1738 | `./node_modules/.bin/mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1726 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1715 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1836 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1824 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1804 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1797 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1791 | `npm run lint && npm run mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1784 | `nyc mocha --timeout=20000 test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1780 | `mocha test/setup.js test/spec/*.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1773 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1744 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [zeit/ms](https://github.com/zeit/ms) | 1740 | `mocha tests.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1738 | `./node_modules/.bin/mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1737 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1735 | `npm run lint && mocha && npm run typescript` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1733 | `mocha test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1727 | `mocha test --timeout 600000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1715 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1710 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1703 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1526 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1517 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1503 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1500 | `npm run lint && mocha && karma start --single-run` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1493 | `mocha --timeout 10000 ./tests/lib.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1493 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1492 | `npm run lint && npm run mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1490 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1488 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1460 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1458 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1452 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1450 | `standard && istanbul cover _mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1443 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1437 | `npm run prepublishOnly && mocha test/test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1670 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1668 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1643 | `mocha ./test/test*.js --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1635 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1619 | `mocha --reporter spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1619 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1492 | `npm run lint && npm run mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1490 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1479 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1460 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1458 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1452 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1450 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1449 | `mocha --opts test/opts/mocha.opts` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1443 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1441 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1536 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1536 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require babel-core/register --recursive --exit` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1535 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1530 | `mocha --check-leaks --require @babel/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1527 | `mocha tests/test-*` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1526 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1517 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1515 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1503 | `mocha test/**/*.spec.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1500 | `npm run lint && mocha && karma start --single-run` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1494 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1493 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1492 | `npm run lint && npm run mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1490 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1488 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1503 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1503 | `mocha test/**/*.spec.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1500 | `npm run lint && mocha && karma start --single-run` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1494 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1493 | `mocha --timeout 10000 ./tests/lib.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1493 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1492 | `npm run lint && npm run mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1490 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1488 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1479 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1460 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1458 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1452 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1450 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1449 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1441 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1437 | `npm run prepublishOnly && mocha test/test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1424 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1420 | `npm run build && mocha -r should` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1420 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1414 | `mocha --recursive test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1405 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1405 | `mocha test --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1404 | `istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1401 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1400 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1395 | `mocha --recursive test/bin` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1391 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1382 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1382 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1380 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1369 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1362 | `NODE_PATH=. mocha **/*.spec.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1362 | `mocha --check-leaks --reporter spec --bail test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1350 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1315 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1312 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1312 | `mocha --timeout 60000 test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1309 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1306 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1305 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1294 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1286 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1282 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1278 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1278 | `mocha --timeout 20000` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1276 | `mocha --timeout 30000 --recursive ./tests` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1265 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1320 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1317 | `mocha test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1315 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1312 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1312 | `mocha --timeout 60000 test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1309 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1309 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1306 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1305 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1301 | `mocha src/test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1300 | `mocha tests/` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1294 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1287 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1286 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1286 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1282 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1280 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1256 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1248 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1248 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1232 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1230 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1226 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1219 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1213 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1210 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [poooi/poi](https://github.com/poooi/poi) | 1204 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1198 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1183 | `mocha --recursive -r tests/setup tests` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1171 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1176 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1166 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1166 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1166 | `mocha --reporter spec --bail --check-leaks test/` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1162 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1160 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1158 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1158 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1153 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1152 | `istanbul cover _mocha test/*.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1142 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 949 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 941 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 940 | `mocha test --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 940 | `mocha --timeout 5000` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 938 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 937 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 936 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 927 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 924 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 920 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 916 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 916 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 915 | `mocha -t 5000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1108 | `npm run convertto:es5 && npm run mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1101 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1101 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1096 | `mocha --recursive --bail --reporter spec test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1096 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1095 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1094 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1088 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1083 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1043 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1018 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1015 | `mocha --colors ./test/*.spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1014 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1012 | `mocha test/*.test.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1009 | `npm run lint && npm run mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1007 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1003 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 993 | `mocha --recursive ./test/*_spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 992 | `npm run lint && mocha -R spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 991 | `mocha spec/*.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 988 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 985 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 982 | `./node_modules/.bin/mocha -R spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 978 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 975 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 969 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 965 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 962 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 961 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 958 | `./node_modules/.bin/mocha --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 957 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 957 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 957 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 956 | `mocha -t 600000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 949 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 947 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 943 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 941 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 940 | `mocha test --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 940 | `mocha --timeout 5000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 949 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 947 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 943 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 941 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 940 | `mocha test --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 940 | `mocha --timeout 5000` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 938 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 937 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 936 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 916 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 916 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 915 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 912 | `./node_modules/.bin/mocha test/**/*` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 904 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 903 | `mocha test` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 894 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 893 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 894 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 893 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 883 | `node_modules/.bin/mocha test/spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 878 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 877 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 874 | `npm run build && istanbul test _mocha test/test.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 856 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 856 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 851 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 849 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 845 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 844 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 843 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 840 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 837 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 836 | `mocha -r babel-register --check-leaks test/index.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 836 | `mocha --harmony tests/**` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 809 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 808 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 804 | `_mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 795 | `mocha test` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 790 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 790 | `mocha index.test.js` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 789 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 787 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 810 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 808 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 804 | `_mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 795 | `mocha test` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 790 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 790 | `mocha index.test.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 827 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 826 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 826 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 826 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 823 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 821 | `npm run lint && mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 818 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 817 | `npm run mocha-test test/integration` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 817 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 814 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 814 | `cake build && mocha ./test/mocha/*.coffee` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 811 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 810 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 804 | `_mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 795 | `mocha test` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 