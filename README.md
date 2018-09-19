# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:08 09/19/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43595 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41333 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40228 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30307 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26585 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23586 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20105 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19199 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17353 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16989 | `mocha` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17353 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16989 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16930 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15449 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14392 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14152 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13813 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13331 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12942 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12727 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12424 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12248 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12112 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11649 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11451 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11405 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10669 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10352 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10287 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10203 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10125 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10081 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9939 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9592 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9447 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9302 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9234 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9076 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8878 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8872 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8832 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8629 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8577 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8549 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8463 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8357 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8224 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8221 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8105 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8043 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7937 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7803 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7771 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7465 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7442 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7379 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7359 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7345 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7205 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7163 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7113 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7109 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6957 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6866 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6784 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6743 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6608 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6553 | `npm run jshint && mocha test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6521 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6326 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6315 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6266 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6051 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6039 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5996 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5894 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5876 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5783 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5767 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5761 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5758 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5620 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4561 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4535 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4520 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4503 | `nyc mocha --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4453 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4449 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4348 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4229 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4225 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4169 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4118 | `node_modules/.bin/mocha test/tests.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4097 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4873 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4866 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4806 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4777 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4770 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4753 | `mocha -R spec 'tests/app'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4730 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4702 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4677 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4578 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4561 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4535 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4520 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4503 | `nyc mocha --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4453 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [tj/ejs](https://github.com/tj/ejs) | 4011 | `mocha --require should --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4004 | `nyc --require ./test/helpers/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3987 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3982 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3945 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3931 | `mocha --check-leaks --reporter spec --bail` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3905 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3876 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3772 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3764 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3698 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3690 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [primus/primus](https://github.com/primus/primus) | 3689 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3678 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3671 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3615 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3603 | `NODE_ENV=test mocha --exit` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3585 | `mocha tests/javascript` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3581 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3570 | `node_modules/.bin/mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3553 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3552 | `NODE_ENV=test mocha test/**/*.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3551 | `mocha --reporter spec --timeout 3000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3530 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3503 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3470 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3469 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3436 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3338 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3321 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3263 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3256 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3154 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3136 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3109 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3105 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3094 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3081 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3077 | `mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3188 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3167 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3154 | `./node_modules/.bin/mocha test/test.*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3152 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3136 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3135 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3112 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3109 | `mocha test/index.js && npm run demo` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3106 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3105 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3094 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3081 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3077 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3054 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3036 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3036 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3032 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3016 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2978 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2965 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2955 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2935 | `mocha -R landing test/index` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2918 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2914 | `eslint . && mocha -t 5000` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2911 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2908 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2892 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2879 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2873 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2872 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2866 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2844 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2830 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2820 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2819 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2813 | `mocha test-node` | 
| [mde/ejs](https://github.com/mde/ejs) | 2807 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2800 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2794 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2760 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2737 | `mocha test.js` | 
| [css/csso](https://github.com/css/csso) | 2735 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2727 | `xo && mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2725 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2723 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2718 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2713 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2670 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2659 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2658 | `mocha --timeout 100000` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2652 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2643 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2613 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2610 | `nyc mocha --timeout=10000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2610 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2592 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2583 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2577 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2556 | `mocha "test/**/*-test.js"` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2528 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2500 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2495 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2492 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2488 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2476 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2475 | `mocha test/src/**/*.unit.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2470 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2465 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2453 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2417 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2400 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2373 | `mocha test/ --no-timeouts` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2366 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2359 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2359 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2356 | `grunt jshint && mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2157 | `cross-env BABEL_ENV=test mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2155 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2140 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2132 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2131 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2118 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2100 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2090 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2074 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2051 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2043 | `mocha && eslint *.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2157 | `cross-env BABEL_ENV=test mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2155 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2140 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2132 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2131 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2118 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2116 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2111 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2100 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2074 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2053 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2051 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2100 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2090 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2074 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2053 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2051 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2043 | `mocha && eslint *.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 2032 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2006 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2005 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2002 | `npm run lint && npm run mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1997 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1995 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1972 | `mocha --require=test/test_helper.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1970 | `mocha --reporter spec --timeout 5000` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1970 | `mocha -c test/index.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1970 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1969 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1962 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1949 | `npm run lint && mocha -R dot && npm run cover` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1944 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1943 | `mocha --bail --reporter spec --check-leaks test/` | 
| [then/promise](https://github.com/then/promise) | 1938 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1932 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1930 | `mocha --require ./test/common --growl test/expect.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1914 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1886 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1882 | `npm run mocha && npm run karma` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1864 | `mocha --compilers js:babel-register` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1860 | `mocha --reporter spec && npm run test-typescript` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1857 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1853 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1844 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1839 | `mocha --reporter spec test/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1839 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1830 | `mocha tests --require @babel/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1823 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1817 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1810 | `mocha --reporter spec --grep .` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1806 | `mocha test/**/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1806 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1787 | `npm run lint && npm run mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1779 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1771 | `mocha test -u bdd -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1757 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1740 | `mocha ./test/basic.js -t 5000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1738 | `mocha test/**/*_test.js --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1736 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1718 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1718 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1708 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1707 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1705 | `npm run lint && npm run mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1701 | `mocha test --timeout 600000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1694 | `mocha compiled_tests/` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1576 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1555 | `mocha --check-leaks --reporter spec --bail` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1555 | `mocha test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1551 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1542 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1539 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1537 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1517 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1516 | `mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1513 | `mocha -u tdd` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1635 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1614 | `mocha tests.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1612 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1611 | `eslint --cache . && tsc && mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1604 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1603 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1600 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1598 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1583 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1576 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1575 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1574 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1567 | `mocha --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1555 | `mocha --check-leaks --reporter spec --bail` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1555 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1555 | `mocha test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1551 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1542 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1539 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1537 | `node_modules/.bin/mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1525 | `nyc mocha --timeout=20000 test.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1518 | `nyc mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1517 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1516 | `mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1513 | `mocha -u tdd` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1487 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1487 | `mocha test/**/*.spec.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1474 | `TEST=all mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1471 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [noble/bleno](https://github.com/noble/bleno) | 1428 | `mocha -R spec test/*.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1425 | `mocha test/unit` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1423 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1416 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1411 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1406 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1403 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1401 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1399 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1398 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1396 | `npm run lint && mocha && karma start --single-run` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1386 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1385 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1381 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1370 | `mocha tests/test-*` | 
| [electron/devtron](https://github.com/electron/devtron) | 1369 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1369 | `mocha --opts test/opts/mocha.opts` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1359 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1350 | `istanbul cover _mocha test -- --timeout 20000` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1350 | `standard && istanbul cover _mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1345 | `mocha -R spec ./test/unit/**` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1344 | `mocha --reporter dot` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1344 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1338 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1335 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1333 | `mocha ./test/test*.js --reporter spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1329 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1317 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1316 | `NODE_PATH=. mocha **/*.spec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1309 | `npm run lint && npm run mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1303 | `mocha spec/exec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1302 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1298 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1295 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1292 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1288 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1287 | `mocha --timeout 60000 test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1284 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1287 | `mocha --timeout 60000 test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1284 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1280 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1278 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1274 | `mocha --check-leaks --reporter spec --bail test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1272 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1268 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1266 | `npm run prepublishOnly && mocha test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1266 | `mocha test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1261 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1259 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1250 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1250 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1246 | `mocha --recursive test` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1245 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1243 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1242 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1236 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1235 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1232 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1231 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1230 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1225 | `istanbul test _mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1217 | `mocha --compilers js:babel-core/register` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1217 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1216 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1215 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [normalize/mz](https://github.com/normalize/mz) | 1215 | `mocha --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1213 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1211 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1209 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1208 | `node ./node_modules/mocha/bin/mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1202 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1200 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1198 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1198 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1191 | `webpack && npm run lint && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1184 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1180 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1155 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1154 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1140 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1136 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1133 | `istanbul cover _mocha test/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1131 | `mocha --timeout 20000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1129 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1129 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1119 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1116 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1119 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1117 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1116 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1112 | `mocha test/*` | 
| [electron/asar](https://github.com/electron/asar) | 1111 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1110 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1109 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1108 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1100 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1090 | `webpack && mocha test/unit` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1093 | `mocha --check-leaks -t 20000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1090 | `webpack && mocha test/unit` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1083 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1081 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1078 | `mocha --timeout 30000 --recursive ./tests` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1075 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1075 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1074 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1073 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1067 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1064 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1060 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1060 | `mocha test --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1055 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1047 | `mocha && standard` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1046 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1046 | `npm-run-all test:jest test:server:mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1044 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1043 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [tomas/needle](https://github.com/tomas/needle) | 1035 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1028 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1028 | `mocha $(find test -name '*.test.js')` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1024 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1018 | `npm run convertto:es5 && npm run mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1017 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1015 | `mocha --async-only` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1011 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1008 | `mocha --recursive -r tests/setup tests` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1004 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 991 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 963 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 955 | `mocha --compilers js:babel-register test/*.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 954 | `mocha "client.test" --compilers js:babel-register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 953 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 952 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 950 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 946 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 945 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 945 | `npm run lint && mocha -R spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 941 | `mocha test` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 930 | `mocha spec/*.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 928 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 927 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 923 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 914 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 911 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 903 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 901 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 899 | `./node_modules/.bin/mocha -R spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 899 | `./node_modules/.bin/mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 897 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 897 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 897 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 897 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 895 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 893 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 889 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 889 | `nyc --check-coverage mocha test/*.test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 889 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 888 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 879 | `mocha --recursive ./test/*_spec.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 879 | `istanbul cover -- _mocha --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 877 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 876 | `mocha --reporter list` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 875 | `npm run lint && npm run mocha:no-functional` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 875 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 875 | `standard && standard ./bin/* && mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 852 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 850 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 849 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 848 | `mocha --reporter spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 845 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 843 | `mocha test/index.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 841 | `npm run lint && mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 839 | `mocha test` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 839 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 838 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 837 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 829 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 829 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 825 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 824 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 821 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 820 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 817 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 811 | `mocha --harmony --full-trace --check-leaks` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 811 | `./node_modules/.bin/mocha test/**/*` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 810 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 810 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 808 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 820 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 817 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 817 | `mocha --async-only` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 813 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 811 | `mocha --harmony --full-trace --check-leaks` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 811 | `./node_modules/.bin/mocha test/**/*` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 810 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 810 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 808 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 808 | `npm run build && istanbul test _mocha test/test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 806 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 806 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 813 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 811 | `mocha --harmony --full-trace --check-leaks` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 811 | `./node_modules/.bin/mocha test/**/*` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 810 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 810 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 808 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 808 | `npm run build && istanbul test _mocha test/test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 806 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 806 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 802 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 801 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 798 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 796 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 796 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 795 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 794 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 790 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 787 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 785 | `mocha -r should --reporter spec test/*.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 783 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 783 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 782 | `xo && mocha -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 781 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 780 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 778 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 776 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 775 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 775 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 767 | `mocha --ui tdd --require ./test/__setup` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 765 | `mocha --recursive -s 15 test/` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 764 | `mocha -R spec src/**/*_test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 744 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 743 | `babel-node node_modules/.bin/_mocha -- test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 741 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 738 | `mocha tests/*.mocha.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 734 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 734 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 734 | `npm run bundle && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 733 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 732 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 731 | `npm run-script jshint && npm run-script mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 730 | `mocha test.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 730 | `mocha --reporter spec build/test/index.js` | 