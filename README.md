# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:01 08/17/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43199 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41128 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39698 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30126 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25811 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24476 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23198 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19747 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18970 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16798 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16561 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15182 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14328 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13958 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13487 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13134 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12711 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12640 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12319 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12237 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11807 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11490 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11169 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11146 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10453 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10120 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10111 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10107 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10027 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9951 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9669 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9619 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9379 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9352 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9099 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9055 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8996 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8717 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8702 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8664 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8495 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8465 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8437 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8319 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8269 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8170 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8061 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7983 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7894 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7806 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7704 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7587 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7555 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7424 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7232 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7215 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7204 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7043 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7038 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6986 | `mocha --compilers js:babel-core/register` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6050 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5968 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5910 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5812 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5720 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5694 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5630 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5624 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5614 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6050 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5968 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5910 | `mocha tests/node.js` | 
| [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) | 5821 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5812 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5720 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5694 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5630 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5624 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5614 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5329 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5288 | `standard && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5196 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5179 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5149 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5087 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4987 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4958 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4958 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4841 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 4828 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4751 | `gulp build; mocha;` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4749 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4737 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4736 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4734 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4695 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4623 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4560 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4467 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4433 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4432 | `mocha --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4429 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4410 | `npm run lint && npm run mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4405 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4327 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4214 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4184 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4148 | `mocha -R spec src` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4144 | `nyc mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4111 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4075 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4024 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4014 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4008 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4005 | `npm run lint ; mocha && mocha test/individual` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4003 | `mocha --timeout=15000 tests/*.test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3977 | `mocha --require should --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3905 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3895 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3855 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3837 | `mocha --check-leaks --reporter spec --bail` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3804 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3800 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3798 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3748 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3670 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3666 | `nyc mocha "test/**/*.test.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3659 | `npm run build && mocha test/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3623 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3605 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3551 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3542 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3526 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3522 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3518 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3464 | `node_modules/.bin/mocha test/lib/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3463 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3446 | `NODE_ENV=test mocha test/**/*.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3439 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3355 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3244 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3243 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3242 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3183 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3173 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3156 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3144 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3142 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3130 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3121 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3082 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3130 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3121 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3082 | `mocha test/*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3065 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3064 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3052 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3051 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3047 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3046 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3026 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3023 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3014 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2991 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2988 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2969 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2943 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2853 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2830 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2823 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2822 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2819 | `mocha -R landing test/index` | 
| [github-tools/github](https://github.com/github-tools/github) | 2810 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2804 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2776 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2762 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2762 | `mocha test-node` | 
| [css/csso](https://github.com/css/csso) | 2723 | `mocha --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2712 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2707 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2703 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2804 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2776 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2762 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2762 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2760 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2735 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2723 | `mocha --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2712 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2707 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2703 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2674 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2654 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2652 | `eslint . && mocha -t 5000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2651 | `mocha --timeout 100000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2644 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2635 | `mocha test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2631 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2621 | `mocha --recursive --watch` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2618 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2615 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2611 | `npm run build && cd test && mocha . --reporter dot` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2609 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2592 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2570 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2538 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2525 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2521 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2517 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2512 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2472 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2459 | `mocha test` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2450 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2449 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2448 | `mocha test/src/**/*.unit.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2440 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2419 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2413 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2410 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2389 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2380 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2365 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2351 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2341 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2321 | `mocha -R spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2310 | `mocha test && npm run lint` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2309 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2302 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2283 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2281 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2269 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2254 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2220 | `mocha --compilers js:babel-register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2218 | `mocha test/ --no-timeouts` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1881 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1867 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1842 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1840 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1836 | `npm run mocha && npm run karma` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1833 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1812 | `mocha --reporter spec test/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1807 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1802 | `mocha && npm run lint` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1800 | `mocha test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1799 | `mocha tests --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1788 | `mocha --compilers js:babel-register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1781 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1766 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1762 | `mocha test/**/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1742 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1739 | `mocha test -u bdd -R spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1728 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1727 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1724 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1706 | `./node_modules/.bin/mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1705 | `mocha ./test/basic.js -t 5000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1705 | `mocha ./test/basic.js -t 5000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1693 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1690 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1687 | `mocha test --timeout 600000` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1683 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1681 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1674 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1669 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1663 | `mocha test/* --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1651 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1647 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1646 | `mocha compiled_tests/` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1636 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1632 | `mocha --expose-gc --slow 300` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1632 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1631 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1629 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1627 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1602 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1595 | `mocha test/setup.js test/spec/*.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1590 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1588 | `mocha test` | 
| [zeit/ms](https://github.com/zeit/ms) | 1575 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1571 | `eslint --cache . && tsc && mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1571 | `./node_modules/mocha/bin/mocha -R spec` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1568 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1561 | `standard "./src/*.js" && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1561 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1551 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1543 | `mocha --reporter spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1533 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1532 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1531 | `mocha test.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1528 | `nyc npm run mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1528 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1525 | `node_modules/.bin/mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1523 | `mocha --check-leaks --reporter spec --bail` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1516 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1505 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1501 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1499 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1490 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1485 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1459 | `nyc mocha --timeout=20000 test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1453 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1420 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1412 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1411 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1409 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1388 | `mocha --check-leaks --require @babel/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1383 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1381 | `mocha test/unit` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1380 | `./node_modules/mocha/bin/mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1379 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1379 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1369 | `npm run build && mocha -r should` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1368 | `TEST=all mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1201 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1201 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1189 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1183 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1183 | `mocha --recursive test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1170 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1170 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1158 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1147 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1146 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [normalize/mz](https://github.com/normalize/mz) | 1203 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1201 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1197 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1189 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1188 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1184 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1183 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1183 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1177 | `mocha --compilers js:babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1170 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1170 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1156 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1269 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1267 | `mocha -R spec ./test/unit/**` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1264 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1263 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1256 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1254 | `npm run lint && npm run mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1252 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1252 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1252 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1245 | `mocha --check-leaks --reporter spec --bail test/` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1244 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1235 | `mocha --recursive test/bin` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1234 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1231 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1224 | `npm run prepublishOnly && mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1222 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1222 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1220 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1219 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1217 | `istanbul test _mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1207 | `npm run lint && npm run mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1205 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [normalize/mz](https://github.com/normalize/mz) | 1203 | `mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1201 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1201 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1197 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1191 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1190 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1191 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1190 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1189 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1188 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [variety/variety](https://github.com/variety/variety) | 1188 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1184 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1183 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1183 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1177 | `mocha --compilers js:babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1170 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1170 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1158 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1156 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1152 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1147 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1146 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1136 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1136 | `webpack && npm run lint && npm run mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1135 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1132 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1129 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1124 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1124 | `mocha $(find test -name '*.test.js')` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1124 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1124 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1122 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1119 | `xo && mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1116 | `npm run mocha:istanbul` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1115 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1114 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [router5/router5](https://github.com/router5/router5) | 1108 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1105 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1102 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1096 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1095 | `mocha --timeout 20000` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1076 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1075 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1074 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1067 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1065 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1059 | `mocha test/tests.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1057 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1055 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1047 | `mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1003 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1003 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 987 | `mocha -R list` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 986 | `npm run convertto:es5 && npm run mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 983 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 979 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 976 | `npm-run-all test:jest test:server:mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 972 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 953 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 953 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 953 | `mocha --recursive -r tests/setup tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 942 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 942 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 941 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 938 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 887 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 884 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 880 | `nyc mocha specs` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 877 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 875 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 874 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 871 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 870 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 869 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 868 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 944 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 942 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 942 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 941 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 938 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 928 | `npm run lint && mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 928 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 927 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 911 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 911 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 905 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 902 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 897 | `mocha -t 600000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 892 | `mocha test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 889 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 887 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 886 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 884 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 880 | `nyc mocha specs` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 877 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 875 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 874 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 871 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 870 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 869 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 868 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 866 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 864 | `mocha -t 5000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 861 | `node_modules/.bin/mocha test/spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 861 | `istanbul cover -- _mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 858 | `standard && standard ./bin/* && mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 856 | `mocha test --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 854 | `nyc --check-coverage mocha test/*.test.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 852 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 851 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 846 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 843 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 841 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 841 | `mocha --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 841 | `mocha --recursive ./test/*_spec.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 841 | `mocha --check-leaks -t 20000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 843 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 841 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 841 | `mocha --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 841 | `mocha --recursive ./test/*_spec.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 841 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 838 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 838 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 836 | `mocha --reporter list` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 834 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 834 | `npm run lint && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 830 | `nyc mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 822 | `mocha test/index.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 819 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 816 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 815 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 814 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 813 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 813 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 810 | `mocha --async-only` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 809 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 804 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 801 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 799 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 797 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 797 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 795 | `mocha --harmony --full-trace --check-leaks` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 777 | `xo && mocha -R spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 776 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 776 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 770 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 770 | `mocha test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 763 | `mocha -R spec src/**/*_test.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 761 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 761 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 766 | `mocha --no-timeouts` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 763 | `mocha -R spec src/**/*_test.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 761 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 761 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 760 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 759 | `mocha --recursive -s 15 test/` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 759 | `./node_modules/.bin/mocha test/**/*` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 756 | `mocha -r should --reporter spec test/*.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 753 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 712 | `./bin/selenium-standalone install && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 709 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 708 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 706 | `mocha ./test/index.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 698 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 698 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 697 | `mocha --harmony --reporter spec --exit` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 696 | `./node_modules/.bin/mocha -t 60000` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 739 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 738 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 738 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 737 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 736 | `nyc mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 734 | `mocha tests/*.mocha.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 730 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 729 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 729 | `babel-node node_modules/.bin/_mocha -- test` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 729 | `mocha test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 728 | `mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 725 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 709 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 708 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 706 | `mocha ./test/index.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 705 | `mocha ./test/test.js --timeout 1000000` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 698 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 698 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 697 | `mocha --harmony --reporter spec --exit` | 