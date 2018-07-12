# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:10 07/12/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42663 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40934 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39180 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29855 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24289 | `npm run lint && npm run mocha-node-test` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24235 | `cross-env NODE_ENV=test mocha` | 
| [lord/slate](https://github.com/lord/slate) | 23833 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22762 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19372 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18688 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16563 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16258 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14804 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14241 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13726 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13047 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12944 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12567 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12533 | `./node_modules/.bin/mocha test/` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12439 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12211 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12203 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11502 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11324 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10844 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10818 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10220 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9916 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 9910 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9889 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9874 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9841 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9443 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9276 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9269 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9066 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8933 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8900 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8785 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8513 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8455 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8437 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8404 | `mocha --check-leaks -R dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8354 | `mocha tests/*.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8339 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8256 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8104 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8006 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7837 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7811 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7801 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7607 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7537 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7476 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7441 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7376 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7317 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 7094 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7063 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7038 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6932 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6853 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6845 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6833 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6586 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6336 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6181 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6170 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6117 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6070 | `mocha; jshint *.js lib` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6042 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6004 | `mocha test/test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5909 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5806 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5714 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5697 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5667 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5639 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5486 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5456 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5358 | `mocha --timeout 10000 && npm run lint` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5344 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5199 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5172 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5156 | `mocha --color` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5130 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5014 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4923 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4833 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4822 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4805 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4803 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [santinic/how2](https://github.com/santinic/how2) | 4722 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4721 | `mocha -R spec 'tests/app'` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4701 | `gulp build; mocha;` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4687 | `mocha --reporter spec -t 8000` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4670 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4642 | `mocha test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4542 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4425 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4423 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4382 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4373 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4310 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4306 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4264 | `npm run lint && npm run mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4216 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4126 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4036 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4034 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4024 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3989 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3987 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3940 | `mocha --require should --reporter spec` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3936 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3936 | `npm run lint ; mocha && mocha test/individual` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3915 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3902 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3888 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3804 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3803 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3726 | `mocha --check-leaks --reporter spec --bail` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3721 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3688 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3667 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3647 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3616 | `npm run build && mocha test/*.test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3589 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3573 | `mocha tests/javascript` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3571 | `nyc mocha "test/**/*.test.js"` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3555 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3535 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3520 | `mocha --reporter spec --timeout 3000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3515 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3512 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3495 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 3488 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3462 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3454 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3444 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3434 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3416 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3398 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3364 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3234 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3219 | `NODE_ENV=test mocha --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3173 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3158 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3153 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3145 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3133 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3123 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3076 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3064 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3052 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3017 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3008 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2931 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2898 | `export TESTING=true; mocha --reporter list` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2884 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2861 | `mocha -R spec --recursive src/test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2855 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2854 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2850 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2845 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2825 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2818 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2815 | `istanbul cover _mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2805 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2799 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2797 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2794 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2789 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2783 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2761 | `npm run mocha && npm run lint` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2884 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2871 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2866 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2861 | `mocha -R spec --recursive src/test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2855 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2854 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2850 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2845 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2825 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2818 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2815 | `istanbul cover _mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2805 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2799 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2797 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2794 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2789 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2783 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2761 | `npm run mocha && npm run lint` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2618 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2612 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2604 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2604 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2602 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2576 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2569 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2564 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2554 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2554 | `nyc --reporter=html --reporter=text mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2546 | `npm run build && cd test && mocha . --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2529 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2508 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2488 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2464 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2462 | `mocha "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2569 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2564 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2554 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2554 | `nyc --reporter=html --reporter=text mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2546 | `npm run build && cd test && mocha . --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2529 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2508 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2488 | `nyc mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2466 | `mocha --reporter=spec test/*-test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2464 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2462 | `mocha "test/**/*-test.js"` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2434 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2431 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2060 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2060 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2008 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2004 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1996 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1952 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1940 | `mocha --compilers js:babel-core/register __tests__` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2270 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2265 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2249 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2245 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2231 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2217 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2217 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2207 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2207 | `mocha --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2004 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1996 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1968 | `nyc npm run _mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1963 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1957 | `mocha --require=test/test_helper.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1952 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1940 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1938 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1927 | `mocha --reporter spec --timeout 5000` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1924 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1923 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1918 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1916 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1908 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1908 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1896 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1891 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1884 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1880 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1859 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1857 | `mocha test/*.test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1850 | `npm run lint && npm run mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1844 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1838 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1827 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1816 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1798 | `npm run mocha && npm run karma` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1792 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1791 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1785 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1779 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1767 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1764 | `mocha && npm run lint` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1758 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1755 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1755 | `mocha --reporter spec test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1750 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1744 | `mocha tests --compilers js:babel-core/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1740 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1737 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1722 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1721 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1719 | `mocha test/**/*.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1710 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1709 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1706 | `mocha test -u bdd -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1706 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1700 | `mocha --compilers js:babel-register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1696 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1696 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1675 | `npm run lint && mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1671 | `mocha test --timeout 600000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1668 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1667 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1657 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1656 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1641 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1640 | `npm run lint && npm run mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1630 | `mocha spec` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1630 | `mocha test/* --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1624 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1621 | `mocha && size-limit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1612 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1595 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1591 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1570 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1569 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1563 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1557 | `./node_modules/mocha/bin/mocha -R spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1495 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1492 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1491 | `mocha --check-leaks --reporter spec --bail` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1488 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1485 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1482 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1475 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1472 | `nyc npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1464 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1457 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1446 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1497 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1497 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1495 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1492 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1492 | `mocha -u tdd` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1491 | `mocha --check-leaks --reporter spec --bail` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1488 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1485 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1482 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1475 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1472 | `nyc npm run mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1471 | `mocha test` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1464 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1457 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1446 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1410 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1398 | `mocha --timeout 10000 ./tests/lib.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1393 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1388 | `nyc mocha --timeout=20000 test.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1386 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1382 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1377 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1374 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1357 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1350 | `npm run build && mocha -r should` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1348 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1344 | `mocha --check-leaks --require @babel/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1341 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1238 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1236 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1232 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1211 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1205 | `mocha src/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1204 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1204 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1197 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1195 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1194 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1194 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1193 | `mocha -R spec ./test/unit/**` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1192 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1192 | `mocha test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1190 | `mocha ./test/test*.js --reporter spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1187 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1187 | `mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1181 | `npm run lint && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1179 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1175 | `mocha --recursive test/bin` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1169 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1169 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1165 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1162 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1160 | `npm run prepublishOnly && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1160 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1159 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1157 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1157 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1155 | `mocha --recursive test` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1149 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1147 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1146 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1137 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1133 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1130 | `mocha --compilers js:babel-core/register` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1113 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1112 | `mocha $(find test -name '*.test.js')` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1108 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1106 | `xo && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1103 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1102 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1099 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1095 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1095 | `mocha test/*` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1093 | `NODE_PATH=. mocha **/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1093 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1091 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1069 | `webpack && npm run lint && npm run mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1065 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1063 | `standard && mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1063 | `npm run lint && mocha --require @babel/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1060 | `istanbul test _mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1060 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1051 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [electron/asar](https://github.com/electron/asar) | 1049 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1046 | `mocha --recursive --bail --reporter spec test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1039 | `npm run mocha:istanbul` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1039 | `webpack && mocha test/unit` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1038 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1036 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1035 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1051 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [electron/asar](https://github.com/electron/asar) | 1049 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1046 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1045 | `mocha test/tests.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1039 | `npm run mocha:istanbul` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1039 | `webpack && mocha test/unit` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1038 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1036 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1035 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1025 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1021 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1019 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1019 | `standard && mocha -b` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 964 | `mocha --reporter spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 958 | `npm run convertto:es5 && npm run mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 948 | `mocha --timeout 30000 --recursive ./tests` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 947 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 921 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 917 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 916 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 915 | `npm run lint && mocha -R spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 912 | `mocha test --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 901 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 897 | `mocha tests` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 896 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 895 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 948 | `mocha --timeout 30000 --recursive ./tests` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 947 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 938 | `mocha "client.test" --compilers js:babel-register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 929 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 925 | `mocha --reporter spec --bail --check-leaks test/` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 925 | `mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 917 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 916 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 915 | `npm run lint && mocha -R spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 912 | `mocha test --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 901 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 900 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 897 | `mocha tests` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 896 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 895 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 895 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 901 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 900 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 897 | `mocha tests` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 896 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 895 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 895 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 889 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 886 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 885 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 883 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 879 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 879 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 877 | `mocha -t 600000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 876 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 868 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 863 | `nyc mocha specs` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 863 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 862 | `npm run lint && npm run mocha:no-functional` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 855 | `eslint test && mocha --compilers js:babel/register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 854 | `node_modules/.bin/mocha test/spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 854 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 848 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 848 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 847 | `standard && standard ./bin/* && mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 845 | `./node_modules/.bin/mocha -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 844 | `mocha test --compilers js:babel-register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 841 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 840 | `./node_modules/.bin/mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 839 | `istanbul cover -- _mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 837 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 836 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 833 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 830 | `mocha test` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 823 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 823 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 819 | `mocha --reporter list` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 819 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 818 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 817 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 816 | `npm run lint && mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 808 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 806 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 806 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 805 | `nyc --check-coverage mocha test/*.test.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 805 | `nyc --check-coverage mocha test/*.test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 802 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 802 | `cake build && mocha ./test/mocha/*.coffee` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 799 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 799 | `mocha --recursive ./test/*_spec.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 797 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 796 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 793 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 792 | `mocha test` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 790 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 793 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 792 | `mocha test` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 790 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 786 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 784 | `mocha --colors --reporter spec test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 782 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 780 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 779 | `mocha --harmony --full-trace --check-leaks` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 778 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 749 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 748 | `mocha --no-timeouts` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 746 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 739 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 735 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 734 | `mocha test` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 732 | `mocha -r should --reporter spec test/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 732 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 762 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 761 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 761 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 755 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 752 | `mocha --recursive -s 15 test/` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 752 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 749 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 749 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 749 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 748 | `mocha --no-timeouts` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 747 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 746 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [scality/S3](https://github.com/scality/S3) | 720 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 720 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 718 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 717 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 716 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 716 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 715 | `babel-node node_modules/.bin/_mocha -- test` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 711 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 709 | `nyc mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 729 | `npm run lint && npm run mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 729 | `mocha test.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 728 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 725 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 724 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 724 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [scality/S3](https://github.com/scality/S3) | 720 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 720 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 718 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 717 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 717 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 716 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 716 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 662 | `mocha` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 659 | `mocha --bail test/` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 658 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 657 | `npm run lint && mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 656 | `mocha --reporter spec --bail --check-leaks test/` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 654 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 653 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 653 | `mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 650 | `mocha --compilers js:babel-register` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 649 | `mocha --recursive --compilers js:babel-core/register` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 647 | `mocha --exit --use_strict src/*.test.js` | 