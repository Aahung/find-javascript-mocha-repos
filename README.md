# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:50 09/01/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43391 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41231 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39949 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30207 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26218 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24549 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23385 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19928 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19075 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17171 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16882 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16731 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15305 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14357 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14039 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13649 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13232 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12796 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12673 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12370 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11309 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11273 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10545 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10239 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10181 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10153 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10071 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10002 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9450 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9412 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9162 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9749 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9450 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9412 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9166 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9162 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9033 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8776 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8761 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8753 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8514 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8504 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8448 | `mocha --check-leaks -R dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8446 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8337 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8197 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8108 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8082 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7914 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7912 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7733 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7691 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7558 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7444 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7297 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7281 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7279 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7119 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7080 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7052 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6988 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6922 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6733 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6574 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6501 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6455 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6351 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6285 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6272 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6240 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6051 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5991 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5948 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5840 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5754 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5740 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5732 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5710 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5693 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5417 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5409 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5379 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5373 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5357 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5181 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5113 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5059 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5030 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4982 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4952 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4845 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4804 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4780 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4761 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4756 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4738 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4696 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4646 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4628 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4575 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4487 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4475 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4470 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4455 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4437 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4428 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4333 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4256 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4197 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4180 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4152 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4097 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4049 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4041 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4027 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4021 | `npm run lint ; mocha && mocha test/individual` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4000 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3898 | `export TESTING=true; mocha --reporter list` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3897 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3880 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3880 | `mocha --check-leaks --reporter spec --bail` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3879 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3878 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3758 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3658 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3561 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3561 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3551 | `mocha --reporter spec --timeout 3000` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3541 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3533 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3513 | `NODE_ENV=test mocha --exit` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3484 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3473 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3469 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3285 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3272 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3264 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3227 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3181 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3152 | `./node_modules/.bin/mocha test/test.*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3137 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3129 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3112 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3186 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3152 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3149 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3137 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3129 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3112 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3105 | `mocha test/*.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3074 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3073 | `mocha test/index.js && npm run demo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3072 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3066 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3063 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3056 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3037 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3032 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3028 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3010 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3005 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2984 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2908 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2902 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2892 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2887 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2878 | `mocha -R landing test/index` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2873 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2870 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2854 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2844 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2840 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2835 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2817 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2798 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2797 | `mocha -R spec spec spec/reporters` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2778 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2777 | `mocha test-node` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2769 | `eslint . && mocha -t 5000` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2760 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2732 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2798 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2797 | `mocha -R spec spec spec/reporters` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2778 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2777 | `mocha test-node` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2769 | `eslint . && mocha -t 5000` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2760 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2732 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2711 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2706 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2693 | `mocha test.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2683 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2677 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2662 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2656 | `mocha --timeout 100000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2683 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2677 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2662 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2656 | `mocha --timeout 100000` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2646 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2640 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2631 | `mocha --recursive --watch` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2623 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2612 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2599 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2573 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2572 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2559 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2559 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2535 | `mocha "test/**/*-test.js"` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2403 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2393 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2352 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2324 | `mocha test/index.js --reporter dot` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2293 | `mocha test/ --no-timeouts` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2265 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2238 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2228 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2221 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2207 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2172 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2148 | `cross-env BABEL_ENV=test mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1991 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1990 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1985 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1981 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 1980 | `npm run lint && npm run mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1971 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1969 | `mocha --require=test/test_helper.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1953 | `./node_modules/.bin/mocha && npm run jshint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1952 | `mocha --reporter spec --timeout 5000` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1937 | `mocha --bail --reporter spec --check-leaks test/` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1930 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1930 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1929 | `npm run lint && mocha -R dot && npm run cover` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1918 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1904 | `mocha test/*.test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1898 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1896 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1881 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1869 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1863 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1860 | `npm run mocha && npm run karma` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1846 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1844 | `mocha --reporter spec && npm run test-typescript` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1827 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1824 | `mocha --reporter spec test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1823 | `mocha --compilers js:babel-register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1816 | `mocha && npm run lint` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1816 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1815 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1810 | `mocha tests --require babel-core/register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1809 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1805 | `npm run lint && mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1804 | `mocha --timeout 5000` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1795 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1793 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1784 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1773 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1757 | `mocha test -u bdd -R spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1752 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1733 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1730 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1722 | `mocha ./test/basic.js -t 5000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1715 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1701 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1699 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1689 | `mocha test --timeout 600000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1687 | `npm run lint && npm run mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1686 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1682 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1675 | `mocha test/* --reporter spec` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1675 | `mocha test/* --reporter spec` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1666 | `mocha compiled_tests/` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1661 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1661 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1658 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1658 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1640 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1639 | `mocha test` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1638 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1634 | `mocha && size-limit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1631 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1631 | `mocha tests/test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1622 | `mocha test/setup.js test/spec/*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1608 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1594 | `eslint --cache . && tsc && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1594 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1591 | `mocha tests.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1584 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1579 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1574 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1566 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1555 | `mocha --reporter spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1554 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1552 | `./node_modules/.bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1551 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1547 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1542 | `mocha --check-leaks --reporter spec --bail` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1542 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1533 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1533 | `node_modules/.bin/mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1533 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1527 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1521 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [retejs/rete](https://github.com/retejs/rete) | 1514 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1508 | `nyc mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1508 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1507 | `mocha -u tdd` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1499 | `mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1486 | `nyc mocha --timeout=20000 test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1485 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1476 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1460 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1457 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1443 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1434 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1419 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1417 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1416 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1409 | `mocha --check-leaks --require @babel/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1403 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1401 | `TEST=all mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1399 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1399 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1390 | `istanbul cover _mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1389 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1389 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1384 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1373 | `npm run build && mocha -r should` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1370 | `npm run lint && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1368 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1366 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1364 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1360 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [electron/devtron](https://github.com/electron/devtron) | 1359 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1354 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1344 | `mocha tests/test-*` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1341 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1339 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1334 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1332 | `standard && istanbul cover _mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1330 | `NODE_ENV=test mocha tests/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1330 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1329 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1322 | `./node_modules/.bin/mocha test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1319 | `mocha --reporter dot` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1312 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1309 | `mocha -R spec ./test/unit/**` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1304 | `mocha-phantomjs tests/index.html` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1303 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1302 | `mocha ./test/test*.js --reporter spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1302 | `mocha ./test/test*.js --reporter spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1302 | `mocha spec/exec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1287 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1285 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1285 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1282 | `npm run lint && npm run mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1279 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1278 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1276 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1273 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1264 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1262 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1262 | `mocha --check-leaks --reporter spec --bail test/` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1259 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1259 | `mocha test/*.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1242 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1239 | `npm run prepublishOnly && mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1234 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1232 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1231 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1229 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1227 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1221 | `istanbul test _mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1215 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1208 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1217 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1215 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1208 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1207 | `mocha --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1206 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1206 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1206 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1204 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1203 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1202 | `mocha --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1201 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1195 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1194 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1194 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1191 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1182 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1172 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1170 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1169 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1169 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1168 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1168 | `webpack && npm run lint && npm run mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1166 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1154 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1152 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1147 | `npm run lint && mocha --require @babel/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1144 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1143 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1142 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1132 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1128 | `mocha $(find test -name '*.test.js') --exit` | 
| [router5/router5](https://github.com/router5/router5) | 1126 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1124 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1124 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1120 | `istanbul cover _mocha test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1119 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1110 | `mocha --timeout 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1108 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1108 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1100 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1097 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1094 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1082 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1078 | `webpack && mocha test/unit` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1073 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1070 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1063 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1063 | `mocha --reporter spec --bail --check-leaks test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1061 | `mocha --timeout 30000 --recursive ./tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1061 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1060 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1060 | `mocha test/tests.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1057 | `standard && mocha -b` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1047 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1046 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1045 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1033 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1030 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1029 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1028 | `mocha test` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1026 | `npm-run-all test:jest test:server:mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1025 | `mocha test --compilers js:babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1024 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1022 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1012 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1012 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1011 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1008 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1003 | `mocha --colors ./test/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1002 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 996 | `npm run convertto:es5 && npm run mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 994 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 989 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 987 | `mocha --recursive -r tests/setup tests` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 984 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 978 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 976 | `mocha --reporter spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 975 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 973 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 952 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 950 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 949 | `mocha --compilers js:babel-register test/*.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 946 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 946 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 946 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 945 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 945 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 944 | `mocha --timeout 5000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 941 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 935 | `npm run lint && mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 927 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 921 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 919 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 918 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 916 | `mocha test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 914 | `mocha ./test/index.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 914 | `mocha test` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 905 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 904 | `mocha -t 600000` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 898 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 894 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 892 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 892 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 890 | `nyc mocha specs` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 890 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 886 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 885 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 883 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 883 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 880 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 878 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 877 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 869 | `mocha --timeout 200000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 868 | `mocha test --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 867 | `nyc --check-coverage mocha test/*.test.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 867 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 867 | `mocha -t 5000` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 867 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 865 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 864 | `node_modules/.bin/mocha test/spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 862 | `standard && standard ./bin/* && mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 861 | `mocha --recursive ./test/*_spec.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 849 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 847 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 847 | `istanbul cover _mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 846 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 845 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 844 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 843 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 836 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 833 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 832 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 833 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 832 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 829 | `mocha test/index.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 828 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 824 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 824 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 824 | `mocha test` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 822 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 820 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 818 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 816 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 814 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 813 | `mocha tests/*.test.js --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 809 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 806 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 805 | `mocha --harmony --full-trace --check-leaks` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 804 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 802 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 801 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 796 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 794 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 794 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 793 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 793 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 792 | `npm run mocha-test test/integration` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 792 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 791 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 790 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 789 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 789 | `mocha --colors --reporter spec test.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 788 | `mocha --exit --use_strict src/*.test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 783 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 782 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 778 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 778 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 775 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 775 | `./node_modules/.bin/mocha test/**/*` | 
| [developit/decko](https://github.com/developit/decko) | 774 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 771 | `mocha --no-timeouts` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 771 | `mocha test` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 770 | `mocha -r should --reporter spec test/*.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 769 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 764 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 763 | `mocha --recursive -s 15 test/` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 759 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 759 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 757 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 753 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 748 | `nyc mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 724 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 716 | `./bin/selenium-standalone install && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 711 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [koajs/static](https://github.com/koajs/static) | 709 | `mocha --harmony --reporter spec --exit` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 709 | `mocha` | 