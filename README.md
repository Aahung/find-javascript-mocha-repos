# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:59 08/24/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43298 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41185 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39808 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30165 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26008 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24516 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23286 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19847 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19022 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17105 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16845 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16623 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15265 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14343 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13997 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13558 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13179 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12755 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12656 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12344 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12235 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11862 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11521 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11241 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11205 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10497 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10199 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10143 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10131 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10053 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9971 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8484 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8444 | `mocha --check-leaks -R dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8344 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8072 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8035 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7907 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7723 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7558 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7438 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7263 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7242 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7078 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7059 | `xo && mocha test/*.js --timeout 100000` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8072 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8035 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7907 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7865 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7723 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7644 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7558 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7438 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7263 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7242 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7240 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7078 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7059 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7019 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6920 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6905 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6711 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6514 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6480 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6403 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6272 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6267 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6239 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6234 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5979 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5922 | `mocha tests/node.js` | 
| [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) | 5834 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5827 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5730 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5713 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5679 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5668 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5661 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5353 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5325 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5307 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5300 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5180 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5148 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5097 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5030 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4996 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4975 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4942 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4842 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4775 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4764 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4748 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4743 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4735 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4695 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4634 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4592 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4574 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4475 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4453 | `mocha --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4440 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4436 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4435 | `npm run lint && npm run mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4412 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4331 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4214 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4171 | `mocha -R spec src` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4148 | `nyc mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4141 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4089 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4029 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4024 | `mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4023 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4015 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4014 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3980 | `mocha --require should --reporter spec` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3898 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3878 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3862 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3857 | `mocha --check-leaks --reporter spec --bail` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3842 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3836 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3830 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3757 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3691 | `nyc mocha "test/**/*.test.js"` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3579 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3547 | `mocha --reporter spec --timeout 3000` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3538 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3528 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3528 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3476 | `NODE_ENV=test mocha --exit` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3470 | `NODE_ENV=test mocha test/**/*.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3465 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3443 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3375 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3375 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3264 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3255 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3254 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3233 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3199 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3173 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3170 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3147 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3145 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3132 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3127 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3199 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3173 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3170 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3147 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3145 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3132 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3127 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3097 | `mocha test/*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3090 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3068 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3061 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3061 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3055 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3055 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3045 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3029 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3023 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3014 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3002 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2884 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2874 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2869 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2860 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2844 | `mocha -R landing test/index` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2837 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2832 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2828 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2827 | `istanbul cover _mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2821 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [github-tools/github](https://github.com/github-tools/github) | 2814 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2781 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2773 | `mocha test-node` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2767 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2745 | `node_modules/.bin/mocha --reporter spec` | 
| [mde/ejs](https://github.com/mde/ejs) | 2732 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2729 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2767 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2745 | `node_modules/.bin/mocha --reporter spec` | 
| [mde/ejs](https://github.com/mde/ejs) | 2732 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2710 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2707 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2702 | `eslint . && mocha -t 5000` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2702 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2695 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2668 | `mocha test.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2660 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2654 | `mocha --timeout 100000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2639 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2636 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2627 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2624 | `mocha --recursive --watch` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2668 | `mocha test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2666 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2660 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2654 | `mocha --timeout 100000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2639 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2636 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2627 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2624 | `mocha --recursive --watch` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2617 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2610 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2596 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2571 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2550 | `nyc mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2548 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2547 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2527 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2519 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2477 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2465 | `mocha test` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2457 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2456 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2455 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2454 | `mocha test/unit --require mochahook` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2438 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2436 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2411 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2397 | `nyc --reporter=html --reporter=text mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2388 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2388 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2348 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2331 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2327 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2312 | `mocha test/index.js --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2311 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2285 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2284 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2283 | `mocha && eslint .` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2264 | `mocha test/ --no-timeouts` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2257 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2223 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2199 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2196 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2160 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2147 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2111 | `standard && mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2109 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2108 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2108 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2100 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2097 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2063 | `nyc npm run _mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2063 | `mocha test/runner.js --reporter spec` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2062 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2057 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2026 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2022 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1991 | `mocha && eslint *.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1986 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1983 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1973 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 1970 | `npm run lint && npm run mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1968 | `mocha -c test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1948 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1947 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1936 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1934 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1928 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [then/promise](https://github.com/then/promise) | 1926 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1925 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1921 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1916 | `mocha --require ./test/common --growl test/expect.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1916 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1897 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1891 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1874 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1864 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1853 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1844 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1843 | `npm run mocha && npm run karma` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1840 | `mocha --reporter spec && npm run test-typescript` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1805 | `mocha test` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1798 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1790 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1786 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1773 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1770 | `mocha test/**/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1746 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1744 | `mocha test -u bdd -R spec` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1743 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1734 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1746 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1744 | `mocha test -u bdd -R spec` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1743 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1734 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1715 | `mocha ./test/basic.js -t 5000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1713 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1708 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1699 | `mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1698 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1697 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1696 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1608 | `mocha test/setup.js test/spec/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1604 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1592 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1575 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1571 | `standard "./src/*.js" && mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1570 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1552 | `./node_modules/.bin/mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1547 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1539 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1542 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1539 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1537 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1533 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1531 | `mocha --check-leaks --reporter spec --bail` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1527 | `node_modules/.bin/mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1523 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1504 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1503 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1500 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1494 | `mocha --recursive` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1571 | `standard "./src/*.js" && mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1570 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1564 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1552 | `./node_modules/.bin/mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1547 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1542 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1539 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1538 | `mocha test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1537 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1533 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1531 | `mocha --check-leaks --reporter spec --bail` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1527 | `node_modules/.bin/mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1523 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1402 | `mocha --check-leaks --require @babel/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1402 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1389 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1387 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1383 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1380 | `TEST=all mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1372 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1369 | `npm run build && mocha -r should` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1361 | `cross-env NODE_ENV=test nyc mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1361 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1358 | `npm run lint && mocha && karma start --single-run` | 
| [electron/devtron](https://github.com/electron/devtron) | 1354 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1353 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1351 | `mocha --opts test/opts/mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1456 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1455 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1441 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1426 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1415 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1415 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1414 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1402 | `mocha --check-leaks --require @babel/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1402 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1389 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1389 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1388 | `istanbul cover _mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1387 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1383 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1380 | `TEST=all mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1372 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1369 | `npm run build && mocha -r should` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1362 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1361 | `cross-env NODE_ENV=test nyc mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1361 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1358 | `npm run lint && mocha && karma start --single-run` | 
| [electron/devtron](https://github.com/electron/devtron) | 1354 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1343 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1338 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1335 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1331 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1329 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1325 | `mocha --recursive` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1325 | `standard && istanbul cover _mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1322 | `./node_modules/.bin/mocha test` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1315 | `NODE_ENV=test mocha tests/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1311 | `mocha --reporter dot` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1307 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1300 | `mocha spec/exec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1299 | `NODE_PATH=. mocha **/*.spec.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1307 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1300 | `mocha spec/exec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1299 | `NODE_PATH=. mocha **/*.spec.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1290 | `mocha -R spec ./test/unit/**` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1286 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1283 | `mocha ./test/test*.js --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1278 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1277 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1277 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1269 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1268 | `npm run lint && npm run mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1268 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1247 | `mocha --recursive test/bin` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1246 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1239 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1228 | `mocha src/test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1227 | `npm run prepublishOnly && mocha test/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1226 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1222 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1219 | `istanbul test _mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1217 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1213 | `npm run lint && npm run mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1219 | `istanbul test _mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1217 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1213 | `npm run lint && npm run mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1204 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1204 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1204 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1204 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1203 | `mocha --reporter spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1198 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1197 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1196 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1193 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1192 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1192 | `mocha --recursive test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1191 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1190 | `mocha --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1190 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1186 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1080 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1078 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1057 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1054 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1052 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1049 | `standard && mocha -b` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1031 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1149 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1149 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1139 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1139 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1137 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1133 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1125 | `mocha $(find test -name '*.test.js')` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1123 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1119 | `npm run mocha:istanbul` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1119 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1118 | `istanbul cover _mocha test/*.js` | 
| [router5/router5](https://github.com/router5/router5) | 1117 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1116 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1073 | `webpack && mocha test/unit` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1062 | `mocha test/tests.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1057 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1054 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1052 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1049 | `standard && mocha -b` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1044 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1044 | `mocha --timeout 30000 --recursive ./tests` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1041 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 988 | `mocha -R list` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 987 | `mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 982 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 973 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 957 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1011 | `mocha --recursive test/unit/` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1006 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1005 | `mocha --async-only` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1000 | `mocha test --compilers js:babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 992 | `npm-run-all test:jest test:server:mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 991 | `npm run convertto:es5 && npm run mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 988 | `mocha -R list` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 987 | `mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 982 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 973 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 973 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 971 | `mocha --recursive -r tests/setup tests` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 960 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 957 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 950 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 947 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 946 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 946 | `mocha "client.test" --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 945 | `mocha --timeout 5000` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 944 | `mocha --compilers js:babel-register test/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 943 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 942 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 941 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 933 | `npm run lint && mocha -R spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 929 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 924 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 914 | `mocha ./test/index.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 913 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 913 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 912 | `mocha spec/*.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 904 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 898 | `mocha -t 600000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 889 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 889 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 898 | `mocha -t 600000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 889 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 889 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 886 | `node_modules/.bin/mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 886 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 885 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 882 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 882 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 879 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 879 | `./node_modules/.bin/mocha --reporter spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 879 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 873 | `./node_modules/.bin/mocha -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 871 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 868 | `istanbul cover -- _mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 867 | `mocha --timeout 200000` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 864 | `mocha -t 5000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 862 | `node_modules/.bin/mocha test/spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 860 | `nyc --check-coverage mocha test/*.test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 858 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 858 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 858 | `standard && standard ./bin/* && mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 851 | `mocha --recursive ./test/*_spec.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 849 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 848 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 844 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 844 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 842 | `mocha --reporter list` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 842 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 842 | `mocha --check-leaks -t 20000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 839 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 839 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 839 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 835 | `npm run lint && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 832 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 831 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 821 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 820 | `mocha test` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 820 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 819 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 816 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 813 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 812 | `mocha --async-only` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 808 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 807 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 807 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 801 | `mocha --harmony --full-trace --check-leaks` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 801 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 799 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 797 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 797 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 793 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 792 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 801 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 799 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 797 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 797 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 793 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 792 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 790 | `npm run build && istanbul test _mocha test/test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 790 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 789 | `npm run mocha-test test/integration` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 789 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 789 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 789 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 788 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 788 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 788 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [edsu/anon](https://github.com/edsu/anon) | 786 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 780 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 779 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 771 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 771 | `mocha test` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 768 | `mocha --no-timeouts` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 768 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 