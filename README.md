# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:02 07/25/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42920 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41011 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39370 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29944 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25128 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24356 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23963 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22919 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19498 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18791 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16651 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16382 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14951 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14284 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13807 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13185 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13013 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12592 | `mocha 'test/**/*.spec.js'` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12592 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12247 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12220 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11612 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11391 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10956 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10946 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10285 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9986 | `mocha` | 
| [svg/svgo](https://github.com/svg/svgo) | 9984 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9978 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 9957 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8875 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8593 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8510 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8463 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8451 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8410 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8381 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8276 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8134 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8030 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8008 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7871 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7816 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7645 | `./node_modules/.bin/mocha test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7573 | `mocha --opts mocha.opts` | 
| [dthree/cash](https://github.com/dthree/cash) | 7546 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8030 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8008 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7871 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7816 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7645 | `./node_modules/.bin/mocha test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7573 | `mocha --opts mocha.opts` | 
| [dthree/cash](https://github.com/dthree/cash) | 7546 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7422 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7395 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7149 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7115 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7098 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6962 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6916 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6902 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6852 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6654 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6382 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6201 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6200 | `mocha; jshint *.js lib` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6193 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6193 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6077 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6041 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5941 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5937 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5871 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5838 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5744 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5690 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5659 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5538 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5520 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5426 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5375 | `mocha --timeout 10000 && npm run lint` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5244 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5190 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5171 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5046 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4935 | `gulp lint && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4928 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4892 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4854 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4836 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4725 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4718 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4702 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4690 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4687 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4568 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4447 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4443 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4428 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4386 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4352 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4343 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4332 | `npm run lint && npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4131 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4089 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4080 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4050 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 4002 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3991 | `mocha --require test/babel-hook test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3978 | `node_modules/.bin/mocha test/tests.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3972 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3955 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3953 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3938 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3881 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3818 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3769 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3758 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3727 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3682 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3671 | `npm run jshint && npm run mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3665 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3653 | `standard && mocha --timeout 60000 test/test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3638 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [primus/primus](https://github.com/primus/primus) | 3630 | `npm run build && mocha test/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3638 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [primus/primus](https://github.com/primus/primus) | 3630 | `npm run build && mocha test/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3619 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3608 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3577 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3575 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3539 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3534 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3529 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3507 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3497 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3456 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3449 | `node_modules/.bin/mocha test/lib/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3448 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3435 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3429 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3373 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3371 | `NODE_ENV=test mocha test/**/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3297 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3269 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3200 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3198 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3185 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3184 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2980 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2951 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2924 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2898 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2877 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2873 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2868 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2857 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2842 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2834 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2833 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2819 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2807 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2804 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2793 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2769 | `mocha --require should --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2764 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2924 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2898 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2883 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2877 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2873 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2868 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2864 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2857 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2842 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2834 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2833 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2832 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2819 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2807 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2805 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2804 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2793 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2779 | `npm run mocha && npm run lint` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2769 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2701 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2697 | `xo && mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2693 | `node_modules/.bin/mocha --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2693 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mde/ejs](https://github.com/mde/ejs) | 2647 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2641 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2641 | `mocha --timeout 100000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2622 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2612 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2608 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2603 | `nyc --reporter=html --reporter=text mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2600 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2568 | `nyc mocha --timeout=10000` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2564 | `mocha test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2563 | `npm run build && cd test && mocha . --reporter dot` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2560 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2557 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2603 | `nyc --reporter=html --reporter=text mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2600 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2592 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2568 | `nyc mocha --timeout=10000` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2564 | `mocha test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2563 | `npm run build && cd test && mocha . --reporter dot` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2560 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2557 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2529 | `export TESTING=true; mocha --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2500 | `nyc mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2491 | `eslint . && mocha -t 5000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2482 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2481 | `mocha "test/**/*-test.js"` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2467 | `mocha --reporter=spec test/*-test.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2303 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2283 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2277 | `mocha test && npm run lint` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2273 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2269 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2239 | `mocha test/index.js --reporter dot` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2229 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2239 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2237 | `mocha && eslint .` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2229 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2216 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2170 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2149 | `mocha --compilers js:babel-register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2147 | `mocha test/ --no-timeouts` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2133 | `cross-env BABEL_ENV=test mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2170 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2149 | `mocha --compilers js:babel-register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2147 | `mocha test/ --no-timeouts` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2133 | `cross-env BABEL_ENV=test mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2106 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2102 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2091 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2079 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2077 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2061 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2032 | `mocha test/runner.js --reporter spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2030 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2013 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1997 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1994 | `nyc npm run _mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1972 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1959 | `mocha --compilers js:babel-core/register __tests__` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1958 | `mocha --require=test/test_helper.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1949 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1944 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1938 | `mocha --reporter spec --timeout 5000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1928 | `mocha && eslint *.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1927 | `mocha --bail --reporter spec --check-leaks test/` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1927 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1922 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [share/sharedb](https://github.com/share/sharedb) | 1916 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1911 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1903 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1901 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1894 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1870 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1857 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1855 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1835 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1827 | `mocha -R spec spec spec/reporters` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1822 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1808 | `npm run mocha && npm run karma` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1790 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1788 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1779 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1776 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1770 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1769 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1768 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1766 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1761 | `mocha --reporter spec --grep .` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1752 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1746 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1736 | `mocha test/**/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1732 | `mocha --compilers js:babel-register` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1726 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1722 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1717 | `mocha test -u bdd -R spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1717 | `mocha test -u bdd -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1708 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1700 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1684 | `npm run lint && mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1679 | `mocha ./test/basic.js -t 5000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1675 | `mocha test --timeout 600000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1673 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1666 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1650 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1646 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1646 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1650 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1646 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1646 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1636 | `mocha test/* --reporter spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1632 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1631 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1624 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1623 | `mocha && size-limit` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1606 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1602 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1597 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1594 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1587 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1580 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1566 | `./node_modules/mocha/bin/mocha -R spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1555 | `mocha test/setup.js test/spec/*.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1551 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1548 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1547 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1543 | `mocha tests.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1543 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1536 | `mocha --reporter spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1534 | `standard "./src/*.js" && mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1518 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1516 | `mocha test` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1515 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1512 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1504 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1503 | `mocha --check-leaks --reporter spec --bail` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1500 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1499 | `node_modules/.bin/mocha --recursive` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1498 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1496 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1488 | `nyc mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1487 | `nyc npm run mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1310 | `./node_modules/.bin/mocha test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1310 | `eslint src && mocha && karma start --single-run` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1308 | `TEST=all mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1308 | `mocha --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1307 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1298 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1293 | `mocha spec/exec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1289 | `mocha tests/test-*` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1283 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1283 | `standard && istanbul cover _mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1274 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1263 | `mocha --timeout 60000 test/` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1248 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1246 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1243 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1239 | `mocha tests` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1417 | `nyc mocha --timeout=20000 test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1411 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1409 | `mocha --timeout 10000 ./tests/lib.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1396 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [retejs/rete](https://github.com/retejs/rete) | 1396 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1394 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1393 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1382 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1375 | `./node_modules/mocha/bin/mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1360 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1360 | `mocha --check-leaks --require @babel/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1358 | `npm run build && mocha -r should` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1357 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1345 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1342 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1338 | `mocha test/unit` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1321 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1319 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1319 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1318 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1310 | `eslint src && mocha && karma start --single-run` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1308 | `TEST=all mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1308 | `mocha --recursive` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1304 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1298 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1293 | `mocha spec/exec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1289 | `mocha tests/test-*` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1285 | `mocha --reporter dot` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1283 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1283 | `standard && istanbul cover _mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1274 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1274 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1263 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1258 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1256 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1253 | `NODE_PATH=. mocha **/*.spec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1246 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1243 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1239 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1239 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1237 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1233 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1233 | `NODE_ENV=test mocha tests/*.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1218 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1217 | `mocha -R spec ./test/unit/**` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1212 | `mocha src/test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1210 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1208 | `mocha ./test/test*.js --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1206 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1201 | `istanbul test _mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1200 | `npm run lint && npm run mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1199 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1199 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1197 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1197 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1197 | `mocha test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1194 | `mocha --recursive test/bin` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1189 | `npm run lint && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1194 | `mocha --recursive test/bin` | 
| [normalize/mz](https://github.com/normalize/mz) | 1190 | `mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1189 | `npm run lint && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1180 | `npm run prepublishOnly && mocha test/test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1178 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1178 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1175 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1171 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1170 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1168 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1166 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1166 | `mocha --recursive test` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1156 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1153 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1150 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1145 | `mocha --compilers js:babel-core/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1138 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1129 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1124 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1121 | `mocha` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1119 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1118 | `mocha $(find test -name '*.test.js')` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1116 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1111 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1111 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1106 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1105 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1104 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1099 | `mocha test/*` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1099 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1098 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1093 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1090 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [router5/router5](https://github.com/router5/router5) | 1087 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1086 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1085 | `npm run lint && mocha --require @babel/register` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1083 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1082 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1080 | `standard && mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1076 | `npm run mocha:istanbul` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1068 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1062 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1057 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1051 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1051 | `mocha test/tests.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1051 | `webpack && mocha test/unit` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1046 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1046 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1043 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1037 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1037 | `mocha --timeout 20000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1035 | `nyc mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1029 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1028 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1022 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1021 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/spectron](https://github.com/electron/spectron) | 1016 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1015 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1012 | `mocha test` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1011 | `mocha $(find test -name '*.test.js')` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1002 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 999 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 997 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 992 | `mocha --async-only` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 984 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 982 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 982 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 980 | `mocha --timeout 30000 --recursive ./tests` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 978 | `mocha -R list` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 970 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 968 | `mocha --reporter spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 966 | `npm run convertto:es5 && npm run mocha` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 966 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 962 | `npm-run-all test:jest test:server:mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 949 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 944 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 942 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 936 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 933 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 930 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 925 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 923 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 920 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 918 | `npm run lint && mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 916 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 907 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 897 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 896 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 892 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 891 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 886 | `mocha -t 600000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 880 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 880 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 879 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 877 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 870 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 867 | `nyc mocha specs` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 864 | `mocha --recursive -r tests/setup tests` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 863 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 863 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 856 | `node_modules/.bin/mocha test/spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 856 | `mocha -t 5000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 856 | `eslint test && mocha --compilers js:babel/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 855 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 855 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 853 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 851 | `./node_modules/.bin/mocha -R spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 851 | `mocha test` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 850 | `istanbul cover -- _mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 848 | `standard && standard ./bin/* && mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 856 | `mocha -t 5000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 856 | `eslint test && mocha --compilers js:babel/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 855 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 855 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 853 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 851 | `./node_modules/.bin/mocha -R spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 851 | `mocha test` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 850 | `istanbul cover -- _mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 848 | `standard && standard ./bin/* && mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 845 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 838 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 836 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 834 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 834 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 828 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 827 | `npm run lint && mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 826 | `mocha --reporter list` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 826 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 826 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 824 | `nyc --check-coverage mocha test/*.test.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 824 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 821 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 820 | `nyc mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 810 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 809 | `mocha test/index.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 809 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 807 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 807 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 803 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 801 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 799 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 798 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 798 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 794 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 798 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 798 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 796 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 794 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 791 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 789 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 785 | `mocha --harmony --full-trace --check-leaks` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 783 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 781 | `npm run mocha-test test/integration` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 773 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 773 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 771 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 770 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [developit/decko](https://github.com/developit/decko) | 769 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 769 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 764 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 763 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 761 | `mocha -R spec src/**/*_test.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 759 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 755 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 