# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:13 07/17/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42751 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40969 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39253 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29885 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24679 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24318 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23875 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22816 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19415 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18729 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16586 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16302 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14855 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14257 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13764 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13104 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12976 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12582 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12550 | `./node_modules/.bin/mocha test/` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12510 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12223 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12211 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11550 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11343 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10880 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10862 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10242 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9948 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 9929 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9921 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9904 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9862 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9469 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9313 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9282 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9094 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8961 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8906 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8811 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8541 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8485 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8443 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8407 | `mocha --check-leaks -R dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8393 | `mocha tests/*.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8354 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8263 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8121 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8019 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7895 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7834 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7816 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7616 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7542 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7511 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7382 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7353 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 7119 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7077 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7058 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6938 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6871 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6868 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6839 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6613 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6355 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6185 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6180 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6137 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6123 | `mocha; jshint *.js lib` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6041 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6025 | `mocha test/test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5941 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5921 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5817 | `mocha tests/node.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5743 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5727 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5680 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5644 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5497 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5483 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5366 | `mocha --timeout 10000 && npm run lint` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5363 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5219 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5171 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5155 | `mocha --color` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5152 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5027 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4924 | `gulp lint && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4847 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4835 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4834 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4826 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4722 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4709 | `gulp build; mocha;` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4688 | `mocha --reporter spec -t 8000` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4679 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4659 | `mocha test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4553 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4434 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4428 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4395 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4373 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4320 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4314 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4294 | `npm run lint && npm run mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4129 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4058 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4056 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4030 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3992 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3990 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3951 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3943 | `mocha --require should --reporter spec` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3942 | `npm run lint ; mocha && mocha test/individual` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3935 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3916 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3888 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3881 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3803 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3736 | `mocha --check-leaks --reporter spec --bail` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3723 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3715 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3674 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3650 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3622 | `npm run build && mocha test/*.test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3617 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3589 | `nyc mocha "test/**/*.test.js"` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3584 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3574 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 3551 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [teambit/bit](https://github.com/teambit/bit) | 3542 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3527 | `mocha --reporter spec --timeout 3000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3525 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3519 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3497 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3475 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3456 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3446 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3433 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3421 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3414 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3368 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3246 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3246 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3169 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3164 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3160 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3138 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3135 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3134 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3123 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3100 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3019 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3012 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2997 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2993 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2984 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2938 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2901 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2876 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2874 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2868 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2860 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2858 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2855 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2826 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2826 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2816 | `istanbul cover _mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2815 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2813 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2901 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2876 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2874 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2868 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2866 | `mocha -R spec --recursive src/test` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2860 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2858 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2855 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2826 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2826 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2816 | `istanbul cover _mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2815 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2813 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2798 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2796 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2791 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2790 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2769 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2750 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2725 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2720 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2718 | `mocha test-node` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2713 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [tj/should.js](https://github.com/tj/should.js) | 2698 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2696 | `mocha -R landing test/index` | 
| [css/csso](https://github.com/css/csso) | 2696 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2696 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2688 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2679 | `node_modules/.bin/mocha --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2636 | `mocha --timeout 100000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2626 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2622 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2616 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2605 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2604 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2584 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2581 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2438 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2434 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2432 | `eslint . && mocha -t 5000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2417 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2414 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2408 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2401 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2396 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2375 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2344 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2342 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2340 | `nyc --reporter=html --reporter=text mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2328 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2299 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2293 | `mocha -R spec` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2434 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2434 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2432 | `eslint . && mocha -t 5000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2417 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2414 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2408 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2401 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2396 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2375 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2375 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2344 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2342 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2340 | `nyc --reporter=html --reporter=text mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2328 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2299 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2293 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2271 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2267 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2259 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2258 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2225 | `mocha && eslint .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2222 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2212 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2210 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2159 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2137 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2131 | `cross-env BABEL_ENV=test mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2121 | `mocha test/ --no-timeouts` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2104 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2096 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2086 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2067 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2063 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2047 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2027 | `mocha test/runner.js --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2007 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2006 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2001 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1976 | `nyc npm run _mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1967 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1956 | `mocha --require=test/test_helper.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1954 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1945 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1941 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1930 | `mocha --reporter spec --timeout 5000` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1925 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1924 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1922 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1920 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1920 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1914 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1901 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1899 | `mocha --require ./test/common --growl test/expect.js` | 
| [then/promise](https://github.com/then/promise) | 1895 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1890 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1884 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1872 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1860 | `mocha test/*.test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1855 | `npm run lint && npm run mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1848 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1842 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1827 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1818 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1800 | `npm run mocha && npm run karma` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1792 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1791 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1786 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1746 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1742 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1726 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1723 | `mocha test/**/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1722 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1721 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1716 | `mocha --compilers js:babel-register` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1712 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1709 | `mocha test -u bdd -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1706 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1698 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1679 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1674 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1673 | `mocha ./test/basic.js -t 5000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1716 | `mocha --compilers js:babel-register` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1712 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1709 | `mocha test -u bdd -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1706 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1698 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1695 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1679 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1674 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1673 | `mocha ./test/basic.js -t 5000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1666 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1661 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1659 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1649 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1642 | `npm run lint && npm run mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1641 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1633 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1631 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1625 | `mocha tests/test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1623 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1622 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1597 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1595 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1560 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1546 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1539 | `npm run test:lint && npm run test:mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1539 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1536 | `mocha --reporter spec` | 
| [zeit/ms](https://github.com/zeit/ms) | 1535 | `mocha tests.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1533 | `mocha test/setup.js test/spec/*.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1525 | `standard "./src/*.js" && mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1517 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1277 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1275 | `standard && istanbul cover _mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1258 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1250 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1249 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1243 | `mocha test/*.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1243 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1239 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1238 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1236 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1235 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1222 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1215 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1209 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1465 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1461 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1438 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1410 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1403 | `mocha --timeout 10000 ./tests/lib.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1395 | `nyc mocha --timeout=20000 test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1393 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1389 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1384 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1378 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1374 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1358 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1355 | `npm run build && mocha -r should` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1352 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1349 | `mocha --check-leaks --require @babel/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1349 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [retejs/rete](https://github.com/retejs/rete) | 1349 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [electron/devtron](https://github.com/electron/devtron) | 1336 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1334 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1331 | `mocha test/unit` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1320 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1317 | `mocha --opts test/opts/mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1315 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1313 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1312 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1312 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1310 | `./node_modules/.bin/mocha test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1310 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1310 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1304 | `mocha --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1303 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1297 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1297 | `eslint src && mocha && karma start --single-run` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1293 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1291 | `mocha spec/exec.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1290 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1288 | `TEST=all mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1279 | `mocha tests/test-*` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1277 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1275 | `standard && istanbul cover _mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1258 | `mocha --timeout 60000 test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1256 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1250 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1244 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1243 | `mocha test/*.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1243 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1239 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1238 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1236 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1235 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1222 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1215 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1211 | `NODE_ENV=test mocha tests/*.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1209 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1207 | `mocha src/test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1204 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1200 | `mocha -R spec ./test/unit/**` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1200 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1199 | `mocha --check-leaks --reporter spec --bail test/` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1198 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1196 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1195 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1194 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1193 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1189 | `mocha --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1186 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1162 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1162 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1159 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1150 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1148 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1143 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1137 | `mocha --compilers js:babel-core/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1133 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1133 | `NODE_PATH=. mocha **/*.spec.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1148 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1143 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1137 | `mocha --compilers js:babel-core/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1133 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1133 | `NODE_PATH=. mocha **/*.spec.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1119 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1115 | `mocha $(find test -name '*.test.js')` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1114 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1109 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1107 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1105 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1103 | `istanbul cover _mocha test/*.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1098 | `mocha test/*` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1097 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1096 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1096 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1094 | `istanbul test _mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1087 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [router5/router5](https://github.com/router5/router5) | 1084 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1083 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1077 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1075 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1070 | `npm run lint && mocha --require @babel/register` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1070 | `standard && mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1069 | `webpack && npm run lint && npm run mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1067 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1067 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1055 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [electron/asar](https://github.com/electron/asar) | 1053 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1048 | `mocha --recursive --bail --reporter spec test` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1048 | `npm run mocha:istanbul` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1045 | `mocha test/tests.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1044 | `webpack && mocha test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1042 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1037 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1036 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1029 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1029 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1027 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1023 | `standard && mocha -b` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1019 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1018 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1018 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1017 | `mocha --timeout 20000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1012 | `mocha && standard` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [tomas/needle](https://github.com/tomas/needle) | 1009 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1008 | `eslint src test && mocha --compilers babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1008 | `mocha $(find test -name '*.test.js')` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1001 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1000 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 994 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 991 | `mocha --async-only` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 990 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 982 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 980 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 978 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 974 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 967 | `mocha --timeout 30000 --recursive ./tests` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 966 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 966 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 964 | `mocha --reporter spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 962 | `npm run convertto:es5 && npm run mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 956 | `npm-run-all test:jest test:server:mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 948 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 940 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 939 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 931 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 930 | `mocha -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 928 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 926 | `mocha test --compilers js:babel-core/register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 925 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 919 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 917 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 914 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 914 | `npm run lint && mocha -R spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 907 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 905 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 903 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 899 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 890 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 889 | `mocha spec/*.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 887 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 884 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 883 | `mocha -t 600000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 880 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 878 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 876 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 873 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 868 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 864 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 863 | `mocha --timeout 200000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 859 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 856 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 855 | `eslint test && mocha --compilers js:babel/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 854 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 853 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 852 | `mocha -t 5000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 851 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 848 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 848 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 847 | `standard && standard ./bin/* && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 824 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 823 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 821 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 820 | `mocha --reporter list` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 820 | `nyc mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 814 | `npm run lint && mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 812 | `nyc --check-coverage mocha test/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 808 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 807 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 807 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 800 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 798 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 798 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 794 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 794 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 786 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 783 | `mocha --harmony --full-trace --check-leaks` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 781 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 810 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 808 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 807 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 807 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 807 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 806 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 805 | `mocha test/index.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 803 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 802 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 800 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 798 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 798 | `mocha --async-only` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 796 | `mocha test` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 783 | `mocha --harmony --full-trace --check-leaks` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 782 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 781 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 777 | `npm run build && istanbul test _mocha test/test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 776 | `npm run mocha-test test/integration` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 776 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 776 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 775 | `xo && mocha -R spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 774 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 774 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 773 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 770 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 769 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 767 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 767 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [developit/decko](https://github.com/developit/decko) | 766 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 735 | `mocha -r should --reporter spec test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 734 | `mocha test` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 732 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 732 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 729 | `mocha tests/*.mocha.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 726 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 723 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [scality/S3](https://github.com/scality/S3) | 722 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 722 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 721 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 720 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 