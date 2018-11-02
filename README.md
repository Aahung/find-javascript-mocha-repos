# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:25 11/02/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44101 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41597 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40824 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30520 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24821 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24054 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20529 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19522 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17745 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17745 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17361 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17253 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15988 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14482 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14397 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14312 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13554 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13186 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12812 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12549 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12354 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12291 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11891 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11785 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11763 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10985 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10651 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10491 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10421 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10363 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10230 | `mocha --harmony` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8498 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8386 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8327 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8284 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8149 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8083 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7840 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7563 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8386 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8327 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8284 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8149 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8083 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7963 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7840 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7563 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7543 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7541 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7516 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7503 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7500 | `npm run build && istanbul cover _mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7470 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7444 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7253 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7237 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7095 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7049 | `mocha; jshint *.js lib` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7016 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6899 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6890 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6870 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6693 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6500 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6400 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6314 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6263 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6123 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6073 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6059 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6005 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5954 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5911 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5897 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5887 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5797 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5635 | `standard && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5258 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5212 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5195 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5151 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5071 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5046 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4907 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4890 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4845 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4809 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4785 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4784 | `mocha -R spec 'tests/app'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4907 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4890 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4845 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4809 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4785 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4784 | `mocha -R spec 'tests/app'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4739 | `mocha --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4737 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4712 | `mocha --reporter spec -t 8000` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4658 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4655 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4638 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4539 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4515 | `nyc mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4470 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4465 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [teambit/bit](https://github.com/teambit/bit) | 4454 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4353 | `mocha -R spec src` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4346 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4316 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4271 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4225 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4224 | `mocha --timeout=15000 tests/*.test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4204 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4201 | `nyc mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4183 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4141 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4115 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4079 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4077 | `mocha --require test/babel-hook test/*.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4056 | `mocha --check-leaks --reporter spec --bail` | 
| [tj/ejs](https://github.com/tj/ejs) | 4035 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3993 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3910 | `export TESTING=true; mocha --reporter list` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3890 | `NODE_ENV=test mocha --exit` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3883 | `nyc mocha "test/**/*.test.js"` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3867 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3798 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3796 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3784 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3688 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3672 | `NODE_ENV=test mocha test/**/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3664 | `npm run jshint && npm run mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3595 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3592 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3588 | `mocha tests/javascript` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3587 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3564 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3552 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3551 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3545 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3416 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3354 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3303 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3219 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3217 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3211 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3169 | `mocha test/index.js && npm run demo` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3159 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3149 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3120 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3303 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3220 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3219 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3217 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3211 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3208 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3206 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3178 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3175 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3174 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3169 | `mocha test/index.js && npm run demo` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3169 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3162 | `eslint . && mocha -t 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3159 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3149 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3121 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3120 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2856 | `mocha test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2855 | `mocha --require babel-register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2847 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2845 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2843 | `mocha -R spec spec spec/reporters` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2843 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2833 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2828 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2777 | `mocha --require should --reporter spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2746 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2730 | `npm run build && cd test && mocha . --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2723 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2708 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2664 | `mocha --timeout 100000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2910 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2886 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2881 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2867 | `node_modules/.bin/mocha --reporter spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2856 | `mocha test.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2856 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2855 | `mocha --require babel-register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2847 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2845 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2843 | `mocha -R spec spec spec/reporters` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2843 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2843 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2833 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2828 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2781 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2777 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2769 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2746 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2735 | `xo && mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2730 | `npm run build && cd test && mocha . --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2723 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2708 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2693 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2664 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2659 | `mocha --recursive --watch` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2641 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2639 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2623 | `nyc mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2621 | `mocha-phantomjs ./test/index.html` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2621 | `mocha "test/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2614 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2581 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2560 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2555 | `mocha test/unit --require mochahook` | 
| [retejs/rete](https://github.com/retejs/rete) | 2549 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2534 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2533 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2518 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2498 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2494 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2493 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2487 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2464 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2451 | `nyc --reporter=html --reporter=text mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2287 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2268 | `npm run build && mocha --require babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2260 | `mocha --compilers js:babel-register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2230 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2195 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2193 | `nyc npm run _mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2001 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1995 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1962 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1955 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1941 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1937 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1937 | `mocha --compilers js:babel-register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1892 | `mocha && npm run lint` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1889 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1883 | `mocha tests --require @babel/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1866 | `mocha --reporter spec test/*.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1855 | `mocha test/**/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1844 | `mocha test` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1843 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1839 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1832 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1804 | `mocha test` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1803 | `npm run lint && npm run mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1782 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1773 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1758 | `mocha compiled_tests/` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1742 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1727 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1722 | `./node_modules/.bin/mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1721 | `npm run lint && mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1719 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1713 | `mocha test/* --reporter spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1708 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1708 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1705 | `mocha test/setup.js test/spec/*.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1703 | `mocha test/*.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1701 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1682 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1663 | `eslint --cache . && tsc && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1662 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1661 | `mocha tests.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1682 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1679 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1663 | `eslint --cache . && tsc && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1662 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1661 | `mocha tests.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1656 | `mocha && size-limit` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1652 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1652 | `mocha spec` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1649 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1637 | `mocha --expose-gc --slow 300` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1633 | `standard "./src/*.js" && mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1589 | `mocha --reporter spec` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1586 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1586 | `mocha test/test-*.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1582 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1573 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1564 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1547 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1545 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1545 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1547 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1545 | `mocha --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1532 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1525 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1522 | `mocha -u tdd` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1505 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1505 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1494 | `mocha test/**/*.spec.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1488 | `NODE_ENV=test mocha tests/*.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1486 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1480 | `mocha test/unit` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1478 | `mocha --timeout 10000 ./tests/lib.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1473 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1472 | `mocha --check-leaks --require @babel/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1460 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1393 | `npm run build && mocha -r should` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1392 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1392 | `mocha --opts test/opts/mocha.opts` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1390 | `npm run lint && npm run mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1384 | `mocha --reporter dot` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1381 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1355 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1348 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1265 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1263 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1262 | `mocha src/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1258 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1256 | `npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1254 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1254 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1250 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1247 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1245 | `webpack && npm run lint && npm run mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1240 | `istanbul test _mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1232 | `npm run mocha:istanbul` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1230 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1224 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1224 | `npm run lint && mocha --require @babel/register` | 
| [variety/variety](https://github.com/variety/variety) | 1223 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1286 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1279 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1272 | `mocha test --compilers js:babel-core/register` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1266 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1265 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1265 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1264 | `mocha --compilers js:babel-core/register` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1262 | `mocha src/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1258 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1256 | `npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1254 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1254 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1250 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1245 | `webpack && npm run lint && npm run mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1233 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1232 | `npm run mocha:istanbul` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1230 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1224 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1224 | `npm run lint && mocha --require @babel/register` | 
| [variety/variety](https://github.com/variety/variety) | 1223 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1218 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1216 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1211 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1210 | `mocha tests/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1206 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1205 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1199 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 1197 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1199 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 1197 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1183 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [x-tag/core](https://github.com/x-tag/core) | 1177 | `NODE_ENV=test mocha --exit` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1166 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1163 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1161 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1156 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1141 | `xo && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1140 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1129 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1122 | `mocha test/*` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1120 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1117 | `npm-run-all test:jest test:server:mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1115 | `webpack && mocha test/unit` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1113 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1113 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1111 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1108 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1117 | `npm-run-all test:jest test:server:mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1115 | `webpack && mocha test/unit` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1113 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1113 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1111 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1108 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1094 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1092 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1086 | `mocha && standard` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1083 | `mocha --compilers js:babel-register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1082 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1079 | `mocha --recursive --bail --reporter spec test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1078 | `nodeunit test; mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1043 | `mocha --reporter spec test --recursive` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1040 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1018 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1011 | `mocha --colors ./test/*.spec.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1010 | `mocha test` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1052 | `npm run convertto:es5 && npm run mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1046 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1045 | `mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1043 | `mocha --reporter spec test --recursive` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1040 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1037 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1033 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1032 | `mocha --async-only` | 
| [odota/core](https://github.com/odota/core) | 1030 | `NODE_ENV=test mocha --exit` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1011 | `mocha --colors ./test/*.spec.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1010 | `mocha test` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 997 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 997 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 989 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 921 | `mocha test` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 920 | `./node_modules/.bin/mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 919 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 917 | `mocha --recursive ./test/*_spec.js` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 915 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 914 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 914 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 913 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 908 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 908 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 906 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 905 | `mocha test --compilers js:babel-register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 902 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 902 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 892 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 891 | `standard && standard ./bin/* && mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 890 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 888 | `node_modules/.bin/mocha` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 885 | `NODE_ENV=test mocha --exit` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 884 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 879 | `mocha -t 5000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 876 | `mocha --timeout 200000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 875 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 872 | `node_modules/.bin/mocha test/spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 864 | `mocha test/index.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 921 | `mocha test` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 920 | `./node_modules/.bin/mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 919 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 917 | `mocha --recursive ./test/*_spec.js` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 915 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 914 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 914 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 913 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 911 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 908 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 908 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 906 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 905 | `mocha test --compilers js:babel-register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 902 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 902 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 896 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 893 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 892 | `istanbul cover -- _mocha --reporter spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 888 | `node_modules/.bin/mocha` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 885 | `NODE_ENV=test mocha --exit` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 885 | `./node_modules/.bin/mocha --globals angular,require` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 884 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 879 | `mocha -t 5000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 876 | `mocha --timeout 200000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 875 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 872 | `node_modules/.bin/mocha test/spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 872 | `node_modules/.bin/mocha test/spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 864 | `mocha test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 859 | `mocha test` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 859 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 857 | `mocha --reporter list` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 857 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 856 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 853 | `istanbul cover _mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 853 | `istanbul cover _mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 850 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 848 | `mocha --check-leaks -t 20000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 846 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 845 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 840 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 840 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 839 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 836 | `./node_modules/.bin/mocha test/**/*` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 834 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 832 | `npm run build && istanbul test _mocha test/test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 832 | `npm run build && istanbul test _mocha test/test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 826 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 826 | `mocha --opts mocha.opts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 824 | `mocha --async-only` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 822 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 821 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 820 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 819 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 752 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 752 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 749 | `npm run-script jshint && npm run-script mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 747 | `mocha --harmony tests/**` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 747 | `mocha test/mocha.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 746 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 745 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 743 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 740 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 735 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 735 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 732 | `./bin/selenium-standalone install && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 800 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 800 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 800 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 796 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 794 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 790 | `mocha test` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 789 | `xo && mocha -R spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 786 | `nyc mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 785 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 783 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 781 | `mocha --no-timeouts` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 780 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 775 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 771 | `mocha --recursive -s 15 test/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 769 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 769 | `mocha -R spec src/**/*_test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 759 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 758 | `npm run lint && npm run mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 757 | `npm run lint && mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 755 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 754 | `nyc mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 754 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 752 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 752 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 749 | `npm run-script jshint && npm run-script mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 747 | `mocha --harmony tests/**` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 747 | `mocha test/mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 735 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 735 | `mocha --reporter spec build/test/index.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 735 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 732 | `./bin/selenium-standalone install && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 729 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 729 | `jenkins-mocha ./tests/*.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 728 | `mocha --harmony --reporter spec --exit` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 727 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 736 | `mocha test.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 735 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 735 | `mocha --reporter spec build/test/index.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 735 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 732 | `./bin/selenium-standalone install && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 729 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 729 | `jenkins-mocha ./tests/*.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 728 | `mocha --harmony --reporter spec --exit` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 727 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 