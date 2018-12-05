# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:34 12/05/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44497 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41753 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41353 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30638 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24984 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24421 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20926 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19768 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18034 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17613 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17474 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16430 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14695 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14576 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14572 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13713 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13362 | `mocha --globals document test` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11989 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11186 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10854 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10669 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10663 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10470 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10313 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10301 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 10313 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10301 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10133 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9599 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9540 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9371 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9370 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9202 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9166 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9150 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8760 | `mocha test/src` | 
| [tj/ejs](https://github.com/tj/ejs) | 4058 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 3864 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3761 | `NODE_ENV=test mocha test/**/*.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3661 | `mocha test/* --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3617 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3594 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3567 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3460 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3457 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3349 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3304 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7456 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7369 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7267 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7264 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7220 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7110 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7060 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6999 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6824 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6649 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6559 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6469 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6336 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6290 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6168 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6162 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6074 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6070 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6069 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6019 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6005 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5991 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5824 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5789 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5614 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5609 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5490 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5418 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5406 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5381 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5264 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5235 | `mocha -r esm` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5198 | `mocha src/**/*Tests.js --harmony` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5165 | `mocha test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5139 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5087 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5069 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4901 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4896 | `gulp build; mocha;` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4868 | `mocha --recursive` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4843 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [teambit/bit](https://github.com/teambit/bit) | 4818 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4815 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4810 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4799 | `./node_modules/.bin/mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4780 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4778 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4728 | `npm run lint && npm run mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4728 | `mocha --reporter spec -t 8000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4674 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4092 | `NODE_ENV=test mocha --exit` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4090 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4058 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4034 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3963 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3920 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3878 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3864 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3805 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3792 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3792 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [primus/primus](https://github.com/primus/primus) | 3761 | `npm run build && mocha test/*.test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3761 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3689 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3661 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3657 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3625 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3623 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3617 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3594 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3570 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3567 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3537 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3501 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3309 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3304 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3260 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3255 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3245 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3209 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3208 | `mocha test/index.js && npm run demo` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3204 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3188 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3156 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3143 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3143 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3124 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3046 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3022 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2974 | `npm run mocha && npm run lint` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2940 | `mocha -R spec --recursive src/test` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2927 | `node_modules/.bin/mocha --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2911 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2908 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2905 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2900 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2896 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2863 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2821 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2974 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2962 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2940 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2934 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2927 | `node_modules/.bin/mocha --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2911 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2908 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2905 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2904 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2900 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2896 | `mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2893 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2864 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2863 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2681 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2676 | `mocha --timeout 100000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2656 | `nyc mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2653 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2605 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2604 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2547 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2541 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2516 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2502 | `mocha --reporter=spec test/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2454 | `mocha test --exit && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2429 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2426 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2421 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2408 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2354 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2341 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2316 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2313 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1406 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1384 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1380 | `mocha --recursive` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1373 | `npm run prepublishOnly && mocha test/test.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1362 | `./node_modules/.bin/mocha test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1362 | `mocha --recursive test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1352 | `mocha test --compilers js:babel-core/register` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1341 | `mocha --recursive` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1328 | `mocha --check-leaks --reporter spec --bail test/` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1322 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1313 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1311 | `mocha-phantomjs tests/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1307 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1300 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1292 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2296 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2292 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2288 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2286 | `nyc --require babel-register npm run _mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2249 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2230 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2205 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2199 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2205 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2199 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2174 | `cross-env BABEL_ENV=test mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2155 | `npm run lint && npm run mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2154 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2149 | `mocha test/runner.js --reporter spec` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2145 | `mocha && eslint *.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2136 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2133 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2124 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2123 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2093 | `mocha --compilers js:babel-core/register __tests__` | 
| [then/promise](https://github.com/then/promise) | 1975 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1953 | `mocha --bail --reporter spec --check-leaks test/` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1951 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1941 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1941 | `mocha && npm run lint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1928 | `mocha tests --require @babel/register` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1913 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1904 | `bmocha --reporter spec test/*.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1887 | `mocha test/**/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1880 | `mocha test` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1870 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1864 | `mocha --reporter spec --grep .` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1824 | `mocha compiled_tests/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1823 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1823 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1821 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1799 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1793 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1751 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1728 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1726 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1717 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1713 | `mocha test --timeout 600000` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1696 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1692 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1685 | `nyc mocha --timeout=20000 test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1674 | `TEST=all mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1665 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1655 | `mocha spec` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1692 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1685 | `nyc mocha --timeout=20000 test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1674 | `TEST=all mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1671 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1665 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1655 | `mocha spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1652 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1645 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1645 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1639 | `mocha test/test-*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1617 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1645 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1645 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1639 | `mocha test/test-*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1637 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1637 | `mocha --check-leaks --reporter spec --bail` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1617 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1612 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1608 | `mocha --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1596 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1593 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1591 | `mocha test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1564 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1560 | `mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1557 | `nyc mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1555 | `NODE_ENV=test mocha tests/*.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1552 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1544 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1535 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1532 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1529 | `mocha -u tdd` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1519 | `mocha ./test/test*.js --reporter spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1502 | `mocha --check-leaks --require @babel/register` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1535 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1534 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1532 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1529 | `mocha -u tdd` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1521 | `mocha test/unit` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1519 | `mocha ./test/test*.js --reporter spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1502 | `mocha --check-leaks --require @babel/register` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1498 | `mocha test/**/*.spec.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1490 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1486 | `mocha --timeout 10000 ./tests/lib.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1482 | `mocha -R spec ./test/unit/**` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1502 | `mocha --check-leaks --require @babel/register` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1499 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1498 | `mocha test/**/*.spec.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1490 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1486 | `mocha --timeout 10000 ./tests/lib.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1482 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1479 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1478 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1478 | `mocha tests/test-*` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1476 | `mocha -R spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1476 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1473 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [noble/bleno](https://github.com/noble/bleno) | 1469 | `mocha -R spec test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1464 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1459 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1458 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1456 | `mocha test/tests.js --timeout=10000` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1455 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1380 | `mocha --recursive` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1378 | `mocha --recursive test/bin` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1376 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1373 | `npm run prepublishOnly && mocha test/test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1365 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1362 | `./node_modules/.bin/mocha test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1352 | `mocha test --compilers js:babel-core/register` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1349 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1349 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1341 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1340 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1337 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1373 | `npm run prepublishOnly && mocha test/test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1365 | `cross-env NODE_ENV=test nyc mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1363 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1363 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1362 | `./node_modules/.bin/mocha test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1362 | `mocha --recursive test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1352 | `mocha test --compilers js:babel-core/register` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1349 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1349 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1341 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1340 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1337 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1295 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1292 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1287 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1283 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1283 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1282 | `npm run mocha:istanbul` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1281 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1280 | `mocha src/test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1276 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1275 | `npm run lint && npm run mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1267 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1263 | `npm run lint && mocha --require @babel/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1262 | `istanbul test _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1255 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1248 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1247 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [variety/variety](https://github.com/variety/variety) | 1241 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1240 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1230 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1229 | `mocha --reporter spec` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1227 | `mocha --timeout 30000 --recursive ./tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1210 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1208 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 1177 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1171 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1168 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1165 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1165 | `mocha --recursive -r tests/setup tests` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1158 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1155 | `xo && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1150 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1149 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1165 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1165 | `mocha --recursive -r tests/setup tests` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1160 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1158 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1155 | `xo && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1150 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1149 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1145 | `npm-run-all test:jest test:server:mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1144 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1139 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1131 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1130 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1128 | `webpack && mocha test/unit` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1131 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1130 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1128 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1125 | `mocha test/*` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1123 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1123 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1113 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1112 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [electron/spectron](https://github.com/electron/spectron) | 1111 | `mocha && standard` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1106 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1103 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1101 | `standard && mocha -b` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1096 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1095 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1092 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1087 | `mocha --recursive --bail --reporter spec test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1084 | `mocha --reporter spec test --recursive` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1078 | `eslint src test && mocha --compilers babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1075 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1074 | `npm run convertto:es5 && npm run mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1074 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1073 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1032 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1024 | `mocha --recursive test/unit/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1021 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 998 | `mocha -R list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 996 | `mocha --reporter spec --bail --check-leaks test/` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 994 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1032 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1024 | `mocha --recursive test/unit/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1021 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 969 | `mocha "client.test" --compilers js:babel-register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 968 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 967 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 964 | `mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 962 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 960 | `mocha --recursive ./test/*_spec.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 955 | `mocha spec/*.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 954 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 949 | `./node_modules/.bin/mocha --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 948 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 947 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 944 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 943 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 861 | `mocha --reporter list` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 856 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 850 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 847 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 845 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 844 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 842 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 837 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 836 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 836 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 835 | `mocha --opts mocha.opts` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 834 | `mocha -r should --exit test/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 947 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 944 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 943 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 942 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 941 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 940 | `mocha -t 600000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 939 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 937 | `./node_modules/.bin/mocha -R spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 934 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 929 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 927 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 927 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 927 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 927 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 926 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 925 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 920 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 918 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 917 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 911 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 911 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 910 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 907 | `standard && standard ./bin/* && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 905 | `istanbul cover -- _mocha --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 900 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 900 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 899 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 889 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 887 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 883 | `mocha --timeout 200000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 847 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 845 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 842 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 837 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 836 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 836 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 835 | `mocha --opts mocha.opts` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 830 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 829 | `mocha && ember test` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 826 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 824 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 811 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 811 | `cake build && mocha ./test/mocha/*.coffee` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 810 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 806 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 802 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 797 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 793 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 793 | `xo && mocha -R spec` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 791 | `_mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 791 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 789 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 837 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 836 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 836 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 835 | `mocha --opts mocha.opts` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 834 | `mocha -r should --exit test/*.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 830 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 830 | `mocha --async-only` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 829 | `mocha && ember test` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 826 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 826 | `mocha -r babel-register --check-leaks test/index.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 824 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 824 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 824 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 821 | `mocha test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [developit/decko](https://github.com/developit/decko) | 819 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 817 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 816 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 814 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 812 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 811 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 811 | `cake build && mocha ./test/mocha/*.coffee` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 811 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 810 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 793 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 793 | `xo && mocha -R spec` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 791 | `_mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 791 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 789 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 781 | `mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 781 | `mocha --harmony tests/**` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 781 | `npm run lint && mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 781 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 781 | `npm run lint && mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 778 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 777 | `mocha --recursive -s 15 test/` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 774 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 773 | `npm run lint && npm run mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 770 | `nyc mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 770 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 770 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 753 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 753 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 750 | `mocha --reporter spec build/test/index.js` | 
| [susam/texme](https://github.com/susam/texme) | 750 | `standard && mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 749 | `./bin/selenium-standalone install && mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 749 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 747 | `mocha tests/*.mocha.js` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 745 | `mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 744 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 743 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [koajs/static](https://github.com/koajs/static) | 742 | `mocha --harmony --reporter spec --exit` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 742 | `mocha test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 753 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 753 | `mocha index.test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 753 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 750 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 749 | `./bin/selenium-standalone install && mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 747 | `mocha tests/*.mocha.js` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 745 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 743 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 