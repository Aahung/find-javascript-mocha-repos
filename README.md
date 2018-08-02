# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:09 08/02/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43028 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41051 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39497 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30002 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25407 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24403 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23027 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19562 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18856 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16715 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16451 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15027 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14298 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13872 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13321 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13073 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12631 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12609 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12271 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12229 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11680 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11422 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11034 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11028 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10351 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10053 | `mocha` | 
| [svg/svgo](https://github.com/svg/svgo) | 10037 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10026 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 9981 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9906 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9575 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9483 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9324 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9259 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9028 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8959 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8950 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8634 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8570 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8531 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8468 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8419 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8406 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8289 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8152 | `mocha --compilers js:babel-register test/test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8105 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8041 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7856 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7658 | `./node_modules/.bin/mocha test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7627 | `mocha --opts mocha.opts` | 
| [dthree/cash](https://github.com/dthree/cash) | 7551 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7490 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7404 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7181 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7156 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7136 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7005 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6951 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6935 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6873 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6718 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6873 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6718 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6414 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6292 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6249 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6216 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6202 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6121 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6044 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5987 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5947 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5942 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5865 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5770 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5703 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5674 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5559 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5558 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5503 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5389 | `mocha --timeout 10000 && npm run lint` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5063 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4942 | `gulp lint && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4897 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4837 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4728 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4724 | `gulp build; mocha;` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4713 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4713 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4584 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4568 | `mocha ./test/runner.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4728 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4724 | `gulp build; mocha;` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4713 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4713 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4692 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4584 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4568 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4495 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4453 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4430 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4395 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4379 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4371 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4358 | `npm run lint && npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4325 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4134 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4133 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4115 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4062 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4030 | `node_modules/.bin/mocha test/tests.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4003 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4002 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3991 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3964 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3964 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3953 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3826 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3804 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3804 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3795 | `mocha --check-leaks --reporter spec --bail` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3735 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3704 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3701 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3688 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 3687 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3672 | `npm run jshint && npm run mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3642 | `npm run build && mocha test/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3625 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3592 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3576 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3553 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3538 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3535 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3516 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3512 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3478 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3455 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3452 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3436 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3431 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3403 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3382 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3345 | `NODE_ENV=test mocha --exit` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3382 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3345 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3289 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3217 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3210 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3206 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3204 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3057 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3045 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3025 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3022 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3022 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3017 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3013 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2997 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2996 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2972 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2970 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2936 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2928 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2896 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2769 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2761 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2743 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2740 | `mocha -R landing test/index` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2739 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2734 | `mocha test-node` | 
| [css/csso](https://github.com/css/csso) | 2711 | `mocha --reporter dot` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2708 | `node_modules/.bin/mocha --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2703 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2699 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mde/ejs](https://github.com/mde/ejs) | 2671 | `mocha --require should --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2644 | `mocha --timeout 100000` | 
| [json5/json5](https://github.com/json5/json5) | 2636 | `nyc --reporter=html --reporter=text mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2631 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2620 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2617 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2616 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2609 | `mocha-phantomjs ./test/index.html` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2596 | `mocha test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2468 | `mocha --reporter=spec test/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2468 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2445 | `mocha test` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2430 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2424 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2420 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2402 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2375 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2371 | `nyc --reporter=html --reporter=text mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2348 | `grunt jshint && mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2311 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2306 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2306 | `mocha -R spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2291 | `mocha test && npm run lint` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2616 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2609 | `mocha-phantomjs ./test/index.html` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2602 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2596 | `mocha test.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2592 | `mocha -R spec spec spec/reporters` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2582 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2579 | `npm run build && cd test && mocha . --reporter dot` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2575 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2567 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2538 | `eslint . && mocha -t 5000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2515 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2500 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2495 | `mocha "test/**/*-test.js"` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2468 | `mocha --reporter=spec test/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2468 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2445 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2441 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2436 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2430 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2424 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2420 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2408 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2402 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2388 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2375 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2371 | `nyc --reporter=html --reporter=text mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2348 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2331 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2089 | `standard && mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2070 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2048 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2042 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2027 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2018 | `nyc npm run _mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1980 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [noble/noble](https://github.com/noble/noble) | 2185 | `mocha -R spec test/*.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2176 | `mocha test/ --no-timeouts` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2160 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2139 | `cross-env BABEL_ENV=test mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2121 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2106 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2104 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2096 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2089 | `standard && mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2070 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2048 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2042 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2027 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2018 | `nyc npm run _mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2004 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1980 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1962 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1959 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1959 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1957 | `mocha --require=test/test_helper.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1943 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1941 | `mocha --reporter spec --timeout 5000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1936 | `mocha && eslint *.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1928 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1924 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1923 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1922 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [then/promise](https://github.com/then/promise) | 1916 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1907 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1905 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1901 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1900 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [pahen/madge](https://github.com/pahen/madge) | 1888 | `npm run lint && npm run mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1881 | `mocha test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1863 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1859 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1837 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1829 | `mocha --reporter spec && npm run test-typescript` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1824 | `npm run mocha && npm run karma` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1788 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1785 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1785 | `mocha && npm run lint` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1782 | `mocha test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1782 | `mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1774 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1772 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1771 | `mocha tests --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1753 | `mocha --compilers js:babel-register` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1748 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1746 | `mocha test/**/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1731 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1724 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1719 | `mocha test -u bdd -R spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1656 | `npm run lint && npm run mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1654 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1650 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1647 | `mocha test/* --reporter spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1644 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1630 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1626 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1625 | `mocha && size-limit` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1600 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1600 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1644 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1630 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1626 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1625 | `mocha && size-limit` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1619 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1611 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1600 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1600 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1583 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1583 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1569 | `./node_modules/mocha/bin/mocha -R spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1565 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1561 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1557 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1553 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [zeit/ms](https://github.com/zeit/ms) | 1551 | `mocha tests.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1544 | `standard "./src/*.js" && mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1539 | `mocha --reporter spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1538 | `mocha test` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1530 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1511 | `mocha --check-leaks --reporter spec --bail` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1509 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1505 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1505 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1501 | `mocha -u tdd` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1498 | `nyc npm run mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1495 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1494 | `nyc mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1471 | `mocha test/**/*.spec.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1471 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1448 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1441 | `mocha test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1432 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1428 | `nyc mocha --timeout=20000 test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1413 | `mocha --timeout 10000 ./tests/lib.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1411 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1441 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1432 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1428 | `nyc mocha --timeout=20000 test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1413 | `mocha --timeout 10000 ./tests/lib.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1411 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1401 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1398 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1378 | `./node_modules/mocha/bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1370 | `mocha --check-leaks --require @babel/register` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1366 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1365 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1361 | `npm run build && mocha -r should` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1361 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1345 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1341 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1337 | `mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1336 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1331 | `eslint src && mocha && karma start --single-run` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1329 | `mocha --opts test/opts/mocha.opts` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1331 | `eslint src && mocha && karma start --single-run` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1329 | `mocha --opts test/opts/mocha.opts` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1325 | `TEST=all mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1325 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1324 | `istanbul cover _mocha test -- --timeout 20000` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1322 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1318 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1316 | `./node_modules/.bin/mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1313 | `mocha --recursive` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1310 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1308 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1308 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1300 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1299 | `mocha tests/test-*` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1295 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1295 | `mocha spec/exec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1292 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1291 | `mocha --reporter dot` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1274 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1265 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1264 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1258 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1252 | `NODE_ENV=test mocha tests/*.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1249 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1248 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1247 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1245 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1245 | `mocha test/*.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1242 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1242 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1234 | `mocha ./test/test*.js --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1233 | `mocha -R spec ./test/unit/**` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1228 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1226 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1222 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1234 | `mocha ./test/test*.js --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1233 | `mocha -R spec ./test/unit/**` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1228 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1226 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1222 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1217 | `mocha src/test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1216 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1213 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1211 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1211 | `istanbul test _mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1209 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1207 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1202 | `mocha test` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1201 | `npm run prepublishOnly && mocha test/test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1200 | `mocha --recursive test/bin` | 
| [normalize/mz](https://github.com/normalize/mz) | 1196 | `mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1195 | `npm run lint && npm run mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1189 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1183 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1182 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1181 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1179 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1175 | `mocha --recursive test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1174 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1174 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1165 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1162 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1153 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1152 | `mocha --compilers js:babel-core/register` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1148 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1144 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1139 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1139 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1127 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1125 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1122 | `mocha $(find test -name '*.test.js')` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1117 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1116 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1114 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1113 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1111 | `istanbul cover _mocha test/*.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1111 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1104 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1100 | `mocha test/*` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1099 | `npm run lint && mocha --require @babel/register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1099 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1099 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [router5/router5](https://github.com/router5/router5) | 1094 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1090 | `npm run mocha:istanbul` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1090 | `webpack && npm run lint && npm run mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1042 | `mocha --timeout 20000` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1037 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1037 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1031 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1029 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1029 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron/spectron](https://github.com/electron/spectron) | 1019 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1018 | `eslint src test && mocha --compilers babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1013 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1054 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1053 | `mocha test/tests.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1052 | `mocha --recursive --bail --reporter spec test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1051 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1050 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1042 | `mocha --timeout 20000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1039 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1037 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1037 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1031 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1029 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1029 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron/spectron](https://github.com/electron/spectron) | 1019 | `mocha && standard` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 983 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 978 | `mocha -R list` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 972 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 969 | `npm-run-all test:jest test:server:mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 969 | `mocha --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 969 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 966 | `mocha test --compilers js:babel-core/register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 951 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 946 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 945 | `mocha "client.test" --compilers js:babel-register` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 943 | `mocha -R spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 940 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 936 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 935 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 934 | `mocha --reporter spec --bail --check-leaks test/` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 934 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 928 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 920 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 911 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 909 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 909 | `mocha tests` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 906 | `mocha --recursive -r tests/setup tests` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 906 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 901 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 900 | `mocha spec/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 901 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 900 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 895 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 889 | `mocha -t 600000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 888 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 885 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 884 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 880 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 878 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 874 | `nyc mocha specs` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 871 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 871 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 866 | `npm run lint && npm run mocha:no-functional` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 865 | `mocha test` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 864 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 863 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 861 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 860 | `mocha -t 5000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 860 | `./node_modules/.bin/mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 859 | `node_modules/.bin/mocha test/spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 859 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 856 | `./node_modules/.bin/mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 854 | `istanbul cover -- _mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 851 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 850 | `standard && standard ./bin/* && mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 847 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 846 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 837 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 837 | `mocha --check-leaks -t 20000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 836 | `nyc --check-coverage mocha test/*.test.js` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 836 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 836 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 835 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 832 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 831 | `mocha --reporter list` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 831 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 830 | `npm run lint && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 830 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 828 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 824 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 823 | `mocha --reporter spec --bail --check-leaks test/` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 823 | `mocha --recursive ./test/*_spec.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 816 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 806 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 805 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 803 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 803 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 803 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 795 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 723 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 721 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 721 | `babel-node node_modules/.bin/_mocha -- test` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 710 | `mocha --reporter spec build/test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 708 | `npm run-script jshint && npm run-script mocha` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 708 | `mocha --exit --use_strict src/*.test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 781 | `npm run build && istanbul test _mocha test/test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 780 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 778 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 778 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 777 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 777 | `mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 777 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 773 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 770 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 768 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 767 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 763 | `mocha test` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 762 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 761 | `mocha -R spec src/**/*_test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 760 | `mocha --no-timeouts` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 755 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 752 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 751 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 748 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 747 | `mocha -r should --reporter spec test/*.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 745 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 