# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:48 11/16/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44257 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41660 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41046 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30563 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25033 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24887 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24188 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20678 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19637 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17874 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17459 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17353 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16158 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14507 | `nyc --reporter=html --reporter=text mocha` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14485 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14472 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13618 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13243 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12866 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12580 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12432 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12299 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11967 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11894 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11849 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11077 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10736 | `set NODE_ENV=test && mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 10649 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10557 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10491 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10442 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10284 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10267 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10245 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9957 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9797 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9561 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9457 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9335 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9244 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9169 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9085 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9049 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8719 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8598 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8512 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8388 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8341 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8303 | `mocha --compilers js:babel-register test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8205 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8161 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7974 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7865 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7617 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7601 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7600 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7598 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [aui/art-template](https://github.com/aui/art-template) | 7585 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7569 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7513 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7448 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5071 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4893 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4868 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4822 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4755 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4720 | `mocha --reporter spec -t 8000` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4717 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4671 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4603 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 4602 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4581 | `nyc mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4491 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4468 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6427 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6391 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6319 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6136 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6132 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6118 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6066 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6035 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5975 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5935 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5933 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5808 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5695 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5588 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5565 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5406 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5374 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5306 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5228 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5187 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5140 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5091 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5071 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4980 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4893 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4868 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4822 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4806 | `mocha --recursive` | 
| [santinic/how2](https://github.com/santinic/how2) | 4801 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4794 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4755 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4744 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4720 | `mocha --reporter spec -t 8000` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4717 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4671 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4603 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 4602 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4581 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4571 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4491 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4468 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4391 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4382 | `mocha -R spec src` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4367 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4349 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4264 | `mocha --timeout=15000 tests/*.test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4251 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4233 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4212 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4204 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4169 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4138 | `npm run lint ; mocha && mocha test/individual` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4130 | `mocha --check-leaks --reporter spec --bail` | 
| [muicss/mui](https://github.com/muicss/mui) | 4085 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4083 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4043 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4012 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3992 | `NODE_ENV=test mocha --exit` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3915 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3912 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3792 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3733 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [primus/primus](https://github.com/primus/primus) | 3732 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3687 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3655 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3612 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3606 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3605 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3591 | `mocha tests/javascript` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3578 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3554 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3591 | `mocha tests/javascript` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3581 | `mocha test/* --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3578 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3565 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3555 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3554 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3494 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3479 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3462 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3446 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3408 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3387 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3370 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3240 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3237 | `mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3232 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3228 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3182 | `mocha test/index.js && npm run demo` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3180 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3162 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3151 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3139 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3117 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3114 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3112 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3105 | `mocha -R landing test/index` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3099 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3056 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3040 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3012 | `eslint . && nyc mocha --recursive` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3008 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2954 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2941 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2940 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2929 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2918 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2897 | `mocha test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2895 | `node_modules/.bin/mocha --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2894 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2892 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2878 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2875 | `mocha test-node` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2874 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2868 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2860 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2848 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2798 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2929 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2918 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2897 | `mocha test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2895 | `node_modules/.bin/mocha --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2894 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2892 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2878 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2875 | `mocha test-node` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2874 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2868 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2862 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2860 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2852 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2848 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2798 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2468 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2465 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2425 | `mocha test && npm run lint` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2416 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2411 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2405 | `mocha test/index.js --reporter dot` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2373 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2331 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2326 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 2312 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2312 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1863 | `npm run lint && mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1847 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1841 | `mocha test` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1809 | `npm run lint && npm run mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1787 | `mocha compiled_tests/` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1783 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1759 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1753 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2344 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2331 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2326 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 2312 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2312 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2295 | `npm run build && mocha --require babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2291 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2290 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2269 | `mocha --compilers js:babel-register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2268 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2221 | `nyc npm run _mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2211 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2209 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2185 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2182 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2182 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2169 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2152 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2140 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2132 | `mocha test/runner.js --reporter spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2131 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2130 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2130 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2130 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2109 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [pahen/madge](https://github.com/pahen/madge) | 2108 | `npm run lint && npm run mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2065 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2045 | `./node_modules/.bin/mocha && npm run jshint` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1945 | `mocha --require ./test/common --growl test/expect.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1941 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1928 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1921 | `mocha && npm run lint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1901 | `mocha --reporter spec && npm run test-typescript` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1895 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1863 | `npm run lint && mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1847 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1841 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1834 | `mocha test -u bdd -R spec` | 
| [then/promise](https://github.com/then/promise) | 1959 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1945 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1945 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1941 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1936 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1928 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1921 | `mocha && npm run lint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1901 | `mocha --reporter spec && npm run test-typescript` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1899 | `mocha tests --require @babel/register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1895 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1753 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1720 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1715 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1709 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1698 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1688 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1685 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1787 | `mocha compiled_tests/` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1783 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1759 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1727 | `npm run lint && mocha && npm run typescript` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1720 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1719 | `mocha test/setup.js test/spec/*.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1727 | `npm run lint && mocha && npm run typescript` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1720 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1719 | `mocha test/setup.js test/spec/*.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1715 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1709 | `mocha test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1709 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1698 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1688 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1687 | `eslint --cache . && tsc && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1685 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1678 | `mocha tests.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1451 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1445 | `mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1440 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1438 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1437 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1434 | `mocha tests/test-*` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1433 | `npm run lint && mocha && karma start --single-run` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1432 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1421 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1411 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1409 | `standard && istanbul cover _mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1406 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1402 | `npm run build && mocha -r should` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1396 | `mocha --reporter dot` | 
| [electron/devtron](https://github.com/electron/devtron) | 1386 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1375 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1374 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1600 | `mocha --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1599 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1589 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1589 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1578 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1577 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1458 | `mocha -R spec ./test/unit/**` | 
| [noble/bleno](https://github.com/noble/bleno) | 1456 | `mocha -R spec test/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1454 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1454 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1451 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1445 | `mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1440 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1438 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1437 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1434 | `mocha tests/test-*` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1433 | `npm run lint && mocha && karma start --single-run` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1432 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1421 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1411 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1410 | `npm run lint && npm run mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1409 | `standard && istanbul cover _mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1406 | `mocha --opts test/opts/mocha.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1494 | `mocha test/unit` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1494 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1489 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1488 | `mocha --check-leaks --require @babel/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1482 | `mocha --timeout 10000 ./tests/lib.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1477 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1475 | `mocha ./test/test*.js --reporter spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1461 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1458 | `mocha -R spec ./test/unit/**` | 
| [noble/bleno](https://github.com/noble/bleno) | 1456 | `mocha -R spec test/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1454 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1454 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1451 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1445 | `mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1440 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1438 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1437 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1434 | `mocha tests/test-*` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1433 | `npm run lint && mocha && karma start --single-run` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1432 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1421 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1411 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1410 | `npm run lint && npm run mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1409 | `standard && istanbul cover _mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1406 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1402 | `npm run build && mocha -r should` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1400 | `istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1396 | `mocha --reporter dot` | 
| [electron/devtron](https://github.com/electron/devtron) | 1386 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1375 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1374 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1367 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1364 | `cross-env NODE_ENV=test nyc mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1361 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1356 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1354 | `./node_modules/.bin/mocha test` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1353 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1342 | `npm run prepublishOnly && mocha test/test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1341 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1337 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1336 | `mocha --recursive test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1333 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1328 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1315 | `mocha --check-leaks --reporter spec --bail test/` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1312 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1311 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1310 | `mocha spec/exec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1309 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1307 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1300 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1294 | `mocha --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1289 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1300 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1300 | `mocha --timeout 60000 test/` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1294 | `mocha --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1289 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1288 | `mocha test/*.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1284 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1278 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1275 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1274 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1273 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1272 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1269 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1267 | `mocha src/test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1265 | `webpack && npm run lint && npm run mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1227 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1223 | `mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1215 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1214 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [router5/router5](https://github.com/router5/router5) | 1205 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1204 | `mocha test` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1199 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1196 | `mocha --timeout 30000 --recursive ./tests` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1185 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1185 | `mocha --timeout 20000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1183 | `mocha --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1101 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1090 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1090 | `standard && mocha -b` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1079 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1078 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1075 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1072 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1071 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1070 | `mocha test/tests.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1061 | `npm run convertto:es5 && npm run mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1060 | `mocha --reporter spec test --recursive` | 
| [electron/spectron](https://github.com/electron/spectron) | 1097 | `mocha && standard` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1086 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1085 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1075 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1071 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1070 | `eslint src test && mocha --compilers babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1070 | `mocha test/tests.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1061 | `npm run convertto:es5 && npm run mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1022 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1013 | `mocha --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1010 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 995 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 995 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 992 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1101 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1097 | `mocha && standard` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1090 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1090 | `standard && mocha -b` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1086 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1085 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1079 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1078 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1075 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1060 | `mocha --reporter spec test --recursive` | 
| [tomas/needle](https://github.com/tomas/needle) | 1051 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1049 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1045 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1041 | `mocha --async-only` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1037 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1033 | `mocha --reporter spec --timeout 3000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1025 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1022 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1013 | `mocha --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1010 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 995 | `mocha -R list` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 992 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 978 | `mocha --reporter spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 975 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 969 | `npm run lint && mocha -R spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 969 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 968 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 968 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 965 | `mocha --compilers js:babel-register test/*.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 964 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 963 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 963 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 963 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 963 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 960 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 950 | `mocha test/*.test.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 949 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 948 | `mocha spec/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 944 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 941 | `mocha tests` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 941 | `mocha --recursive ./test/*_spec.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 917 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 917 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 916 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 914 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 912 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 907 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 902 | `mocha -t 5000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 898 | `istanbul cover -- _mocha --reporter spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 896 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 893 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 892 | `node_modules/.bin/mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 914 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 912 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 910 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 907 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 903 | `standard && standard ./bin/* && mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 902 | `mocha -t 5000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 898 | `istanbul cover -- _mocha --reporter spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 896 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 893 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 892 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 888 | `npm run lint && npm run mocha:no-functional` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 879 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 879 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 874 | `node_modules/.bin/mocha test/spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 872 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 871 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 861 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 857 | `mocha --reporter list` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 857 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 855 | `istanbul cover _mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 851 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 849 | `mocha --check-leaks -t 20000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 848 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 847 | `./node_modules/.bin/mocha test/**/*` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 846 | `npm run lint && npm run mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 845 | `npm run lint && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 844 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 842 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 842 | `npm run build && istanbul test _mocha test/test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 840 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `nyc mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 765 | `npm run lint && mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 763 | `npm run lint && npm run mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 762 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 759 | `nyc mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 753 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 753 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 753 | `mocha test/mocha.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 751 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 750 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 749 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 743 | `jenkins-mocha ./tests/*.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 831 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 831 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 830 | `mocha --harmony --full-trace --check-leaks` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 828 | `mocha --opts mocha.opts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 828 | `mocha --async-only` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 826 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 826 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 821 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 821 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 820 | `mocha -r should --reporter spec test/*.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 819 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 816 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 815 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 791 | `xo && mocha -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 791 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 787 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 786 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 784 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 776 | `mocha` | 