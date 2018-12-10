# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:43 12/10/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44555 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41786 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41417 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30656 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25006 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24484 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20983 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19799 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18075 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18075 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17657 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17504 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16519 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14747 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14609 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14589 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13740 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13393 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12912 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12657 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12564 | `istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12412 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12326 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12098 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12087 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12020 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11218 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10890 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10706 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10692 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10481 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10167 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9612 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9555 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9402 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9378 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9206 | `grunt mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9174 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8772 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8625 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8529 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8410 | `grunt clean:test && mocha --exit` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8402 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8382 | `mocha --compilers js:babel-register test/test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8625 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8529 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8410 | `grunt clean:test && mocha --exit` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8402 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8382 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8357 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8189 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7998 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7909 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7771 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7771 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7715 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7697 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7694 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6843 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6659 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6472 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6338 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6177 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6166 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6087 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6078 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6028 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6022 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6004 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6472 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6338 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6321 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6177 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6166 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6087 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6078 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6028 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6022 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6004 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5828 | `mocha && eslint lib/**` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5418 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5415 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5395 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5267 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5257 | `mocha -r esm` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5199 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5137 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5091 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5090 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4902 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4900 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5137 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5091 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5090 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4902 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4900 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4889 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4885 | `mocha --recursive` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4845 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4820 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4811 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4810 | `./node_modules/.bin/mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4788 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4784 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4740 | `npm run lint && npm run mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4728 | `mocha --reporter spec -t 8000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4694 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4398 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4357 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4316 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4267 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4234 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4220 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4203 | `mocha -R spec ./test --recursive` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4200 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4120 | `NODE_ENV=test mocha --exit` | 
| [muicss/mui](https://github.com/muicss/mui) | 4103 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4063 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3972 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3892 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3875 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3814 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3808 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3772 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3675 | `mocha test/* --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3619 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3594 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3570 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3546 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3507 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3480 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3459 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3453 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3407 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3329 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3461 | `nyc mocha && tsc` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3459 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3453 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3407 | `eslint . && mocha -t 5000` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3407 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3392 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3354 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3329 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3310 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3297 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3275 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3270 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3269 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3262 | `mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3261 | `mocha && tsc -p ./test/types` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3175 | `mocha -R landing test/index --exit` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3173 | `./node_modules/.bin/mocha test/test.*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3160 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3159 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3153 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3123 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3048 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3043 | `eslint . && nyc mocha --recursive` | 
| [mde/ejs](https://github.com/mde/ejs) | 3036 | `mocha --require should --reporter spec` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3025 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2985 | `npm run mocha && npm run lint` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2941 | `mocha -R spec --recursive src/test` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2935 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3051 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3048 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3043 | `eslint . && nyc mocha --recursive` | 
| [mde/ejs](https://github.com/mde/ejs) | 3036 | `mocha --require should --reporter spec` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3025 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2985 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2969 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2956 | `mocha test.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2950 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2941 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2937 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2935 | `node_modules/.bin/mocha --reporter spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2928 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2917 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2910 | `mocha test-node` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2780 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2779 | `npm run build && cd test && mocha . --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2753 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2750 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2749 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2743 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2722 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2689 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2687 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2686 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2685 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2677 | `mocha --timeout 100000` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2675 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2628 | `mocha-phantomjs ./test/index.html` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2614 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2608 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2750 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2749 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2743 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2722 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2706 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2689 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2687 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2686 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2685 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2677 | `mocha --timeout 100000` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2675 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2663 | `nyc mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2628 | `mocha-phantomjs ./test/index.html` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2614 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2608 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2589 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2585 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2522 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2517 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2503 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2488 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2484 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2454 | `mocha && eslint .` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2443 | `mocha --no-colors --reporter spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2430 | `mocha test/index.js --reporter dot` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2428 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2421 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2418 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2388 | `mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2290 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2284 | `mocha --compilers js:babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2261 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2238 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2232 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2208 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2203 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [pahen/madge](https://github.com/pahen/madge) | 2176 | `npm run lint && npm run mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2176 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2176 | `cross-env BABEL_ENV=test mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1793 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1769 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1760 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1731 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1730 | `./node_modules/.bin/mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1727 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1722 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1718 | `mocha test --timeout 600000` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1705 | `nyc mocha --timeout=20000 test.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1697 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1694 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1691 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1684 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1672 | `mocha && size-limit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1659 | `standard "./src/*.js" && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1657 | `mocha spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1653 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1650 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1649 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1645 | `mocha test/test-*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1644 | `mocha --check-leaks --reporter spec --bail` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1619 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1612 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1610 | `mocha --reporter spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1599 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1595 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1581 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1561 | `NODE_ENV=test mocha tests/*.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1560 | `nyc mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1553 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1537 | `mocha ./test/test*.js --reporter spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1534 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1532 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1529 | `mocha -u tdd` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1526 | `mocha test/unit` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1499 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1499 | `mocha test/**/*.spec.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1494 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1489 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1489 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1476 | `mocha -R spec` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1475 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1471 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1464 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1463 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1462 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1457 | `mocha test/tests.js --timeout=10000` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1457 | `npm run lint && mocha && karma start --single-run` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1444 | `npm run lint && npm run mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1441 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1432 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1425 | `mocha --opts test/opts/mocha.opts` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1413 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1463 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1462 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1457 | `mocha test/tests.js --timeout=10000` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1457 | `npm run lint && mocha && karma start --single-run` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1444 | `npm run lint && npm run mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1441 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1432 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1432 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1428 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1425 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1421 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1421 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1413 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1411 | `npm run build && mocha -r should` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1207 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1180 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1165 | `mocha --recursive -r tests/setup tests` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1153 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1150 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1132 | `webpack && mocha test/unit` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1129 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1074 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1059 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1054 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1048 | `mocha --async-only` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1025 | `mocha --recursive test/unit/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1023 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1015 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1261 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1260 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1260 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1249 | `mocha` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1247 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1243 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1242 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1232 | `mocha --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1218 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1217 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1272 | `npm run lint && mocha --require @babel/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1267 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1266 | `mocha tests/` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1261 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1260 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1260 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1249 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1249 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1247 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1243 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1242 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 998 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 980 | `npm run lint && mocha -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 979 | `mocha --compilers js:babel-register test/*.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 977 | `mocha test/*.test.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 973 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 969 | `mocha "client.test" --compilers js:babel-register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 968 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 964 | `mocha --recursive ./test/*_spec.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 963 | `mocha spec/*.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 960 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 953 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 952 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 951 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 947 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 944 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 943 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 942 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 941 | `mocha -t 600000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 941 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 941 | `mocha -t 600000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 941 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 938 | `./node_modules/.bin/mocha -R spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 936 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 929 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 929 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 928 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 927 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 927 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 924 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 920 | `npm run lint && npm run mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 920 | `npm run lint && npm run mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 919 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 919 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 918 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 918 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 911 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 910 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 909 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 909 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 907 | `standard && standard ./bin/* && mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 903 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 900 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 880 | `node_modules/.bin/mocha test/spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 872 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 864 | `mocha --reporter list` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 862 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 859 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 857 | `istanbul cover _mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 856 | `npm run build && istanbul test _mocha test/test.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 874 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 872 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 864 | `mocha --reporter list` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 862 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 859 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 857 | `istanbul cover _mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 856 | `npm run build && istanbul test _mocha test/test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 852 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 852 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 852 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 852 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 774 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 773 | `nyc mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 770 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 761 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 759 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 759 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 758 | `mocha index.test.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 758 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 752 | `standard && mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 751 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 750 | `mocha --reporter spec build/test/index.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 749 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 831 | `mocha --async-only` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 829 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 829 | `mocha && ember test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 826 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 825 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 825 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 821 | `mocha test` | 
| [developit/decko](https://github.com/developit/decko) | 820 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 818 | `./node_modules/.bin/mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 818 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 818 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 817 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 816 | `nyc mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 795 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 794 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 791 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 785 | `npm run lint && mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 784 | `mocha tests --timeout 10000` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 784 | `mocha tests --timeout 10000` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 783 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 779 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 777 | `mocha --recursive -s 15 test/` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 776 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 773 | `nyc mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 771 | `mocha -R spec src/**/*_test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 770 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 785 | `npm run lint && mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 784 | `mocha tests --timeout 10000` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 783 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 779 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 777 | `mocha --recursive -s 15 test/` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 776 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 774 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 773 | `nyc mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 771 | `mocha -R spec src/**/*_test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 770 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 770 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 768 | `mocha test/mocha.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 766 | `babel-node node_modules/.bin/_mocha -- test` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 761 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 759 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 759 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 758 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 758 | `mocha index.test.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 758 | `npm run-script jshint && npm run-script mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 755 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 753 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 752 | `./bin/selenium-standalone install && mocha` | 
| [susam/texme](https://github.com/susam/texme) | 752 | `standard && mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 751 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 750 | `mocha --reporter spec build/test/index.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 749 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 747 | `mocha tests/*.mocha.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 745 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 745 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 715 | `mocha --compilers js:babel-core/register` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 707 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 707 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 707 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 704 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 699 | `mocha --reporter spec` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 698 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 693 | `mocha --reporter spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 691 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 688 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 715 | `mocha --compilers js:babel-core/register` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 712 | `eslint . && mocha` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 707 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 707 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 704 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 707 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 707 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 707 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 699 | `mocha --reporter spec` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 698 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 696 | `mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 696 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 693 | `mocha --reporter spec` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 692 | `mocha` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 688 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [formio/formio](https://github.com/formio/formio) | 684 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 683 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 682 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 688 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [formio/formio](https://github.com/formio/formio) | 684 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 683 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 683 | `mocha test/**/test_*.js` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 682 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 679 | `mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 678 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 657 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 656 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 653 | `npm -s run mocha && npm run -s lint` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 651 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 649 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 648 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 648 | `./node_modules/.bin/mocha --bail` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 648 | `mocha --ui bdd --reporter spec` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 647 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 647 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 647 | `mocha` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 647 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 646 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 644 | `mocha` | 
| [SavjeeTutorials/SavjeeCoin](https://github.com/SavjeeTutorials/SavjeeCoin) | 643 | `mocha tests/*.test.js` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 642 | `node_modules/.bin/mocha` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 628 | `tav --ci && mocha test/index.js` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 628 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 627 | `nyc mocha test.js` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 626 | `mocha --reporter spec` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 625 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 625 | `mocha ./test --bail` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 624 | `npm run lint && npm run mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 621 | `mocha --ui bdd --reporter spec test/` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 621 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nexus-js/ui](https://github.com/nexus-js/ui) | 621 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 620 | `mocha` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 620 | `mocha` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 620 | `nyc --reporter=text --reporter=lcov mocha` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 619 | `mocha` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 619 | `./node_modules/mocha/bin/mocha` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 618 | `mocha test` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 615 | `gulp mocha` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 615 | `gulp build && mocha test.js` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 614 | `mocha && jshint .` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 613 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 653 | `npm -s run mocha && npm run -s lint` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 651 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 649 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 648 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 648 | `./node_modules/.bin/mocha --bail` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 648 | `mocha --ui bdd --reporter spec` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 647 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 647 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 647 | `mocha` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 647 | `mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 647 | `istanbul cover _mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 646 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 644 | `mocha` | 
| [SavjeeTutorials/SavjeeCoin](https://github.com/SavjeeTutorials/SavjeeCoin) | 643 | `mocha tests/*.test.js` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 642 | `node_modules/.bin/mocha` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 641 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 