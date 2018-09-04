# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:09 09/04/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43421 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41248 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40001 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30219 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26267 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24563 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23402 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19958 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19094 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17203 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16892 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16760 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15324 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14365 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14056 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13671 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13251 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12808 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12686 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12375 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12237 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11969 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11575 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11330 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11289 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10569 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10247 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10196 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10162 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10079 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10012 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9801 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9777 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9470 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9420 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9178 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9170 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9037 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8786 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8775 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8765 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8519 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8517 | `mocha test/src` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8468 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8450 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8341 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8201 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8126 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8083 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7928 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7919 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7740 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7717 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7558 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7452 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7311 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7294 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7285 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7131 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7082 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7061 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7012 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6926 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6787 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6746 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6597 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6505 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6474 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6376 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6291 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6279 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6248 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6053 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5993 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5956 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5846 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5775 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5743 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5739 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5718 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5704 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5441 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5418 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5393 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5380 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5369 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5182 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5120 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5069 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5039 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4984 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4978 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4848 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4813 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4781 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4764 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4762 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4740 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4696 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4652 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4644 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4572 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4492 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4489 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4475 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4463 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4438 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4431 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4336 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4275 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4204 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4190 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4152 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4100 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4059 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4048 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4042 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4034 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4023 | `npm run lint ; mocha && mocha test/individual` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4015 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3994 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3906 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3900 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3899 | `export TESTING=true; mocha --reporter list` | 
| [teambit/bit](https://github.com/teambit/bit) | 3898 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3891 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3885 | `mocha --check-leaks --reporter spec --bail` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3879 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3761 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3579 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3561 | `node_modules/.bin/mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3551 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3551 | `mocha --reporter spec --timeout 3000` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3504 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3495 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3484 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3402 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3469 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3402 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3291 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3278 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3268 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3240 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3232 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3192 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3182 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3163 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3153 | `./node_modules/.bin/mocha test/test.*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3140 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3130 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3121 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3109 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3078 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3078 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3077 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3071 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3071 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3064 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3041 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3034 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3030 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2890 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2883 | `mocha -R landing test/index` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2874 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2871 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2855 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2844 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2844 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2837 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2821 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2806 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2798 | `mocha -R spec spec spec/reporters` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2786 | `eslint . && mocha -t 5000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2769 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2731 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2718 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2711 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2766 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2732 | `mocha --reporter dot` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2731 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2718 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2711 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2706 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2688 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2683 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2674 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2657 | `mocha --timeout 100000` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2647 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2639 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2632 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2611 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2600 | `nyc mocha --timeout=10000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2580 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2688 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2683 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2674 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2657 | `mocha --timeout 100000` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2647 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2639 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2632 | `mocha --recursive --watch` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2629 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2611 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2600 | `nyc mocha --timeout=10000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2580 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2574 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2562 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2562 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2539 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2524 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2485 | `mocha --reporter=spec test/*-test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2472 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2472 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2468 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2467 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2461 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2453 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2446 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2415 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2405 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2394 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2352 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2342 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2335 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2328 | `mocha test/index.js --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2307 | `mocha test/ --no-timeouts` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2297 | `mocha && eslint .` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2267 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2085 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2082 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2073 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2065 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2031 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2006 | `mocha && eslint *.js` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1993 | `mocha --compilers js:babel-core/register __tests__` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1992 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1987 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1983 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1971 | `mocha -c test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1958 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1956 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1937 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1937 | `mocha --bail --reporter spec --check-leaks test/` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1934 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1933 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1919 | `mocha --require ./test/common --growl test/expect.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1916 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1908 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kach/nearley](https://github.com/kach/nearley) | 1905 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1898 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1898 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1881 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1876 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1867 | `npm run mocha && npm run karma` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1849 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1844 | `mocha --reporter spec && npm run test-typescript` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1833 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1830 | `mocha --compilers js:babel-register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1824 | `mocha --reporter spec test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1819 | `mocha && npm run lint` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1818 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1818 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1816 | `mocha tests --require babel-core/register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1810 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1807 | `npm run lint && mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1797 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1796 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1788 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1773 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1758 | `mocha test -u bdd -R spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1752 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1742 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1736 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1730 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1729 | `mocha ./test/basic.js -t 5000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1715 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1703 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1702 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1700 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1692 | `mocha test --timeout 600000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1692 | `npm run lint && npm run mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1686 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1682 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [zeit/ms](https://github.com/zeit/ms) | 1598 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1598 | `eslint --cache . && tsc && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1594 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1587 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1584 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1567 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1561 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1558 | `mocha --reporter spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1553 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1548 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1543 | `mocha test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1542 | `mocha --check-leaks --reporter spec --bail` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1609 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1598 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1598 | `eslint --cache . && tsc && mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1594 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1587 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1584 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1575 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1567 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1561 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1510 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1508 | `nyc mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1508 | `mocha -u tdd` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1499 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1485 | `mocha -R spec` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1461 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1508 | `nyc mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1508 | `mocha -u tdd` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1499 | `mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1491 | `nyc mocha --timeout=20000 test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1485 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1477 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1461 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1391 | `istanbul cover _mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1387 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1376 | `npm run lint && mocha && karma start --single-run` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1375 | `npm run build && mocha -r should` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1369 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1369 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1366 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1360 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1356 | `mocha --opts test/opts/mocha.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1343 | `istanbul cover _mocha test -- --timeout 20000` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1341 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1369 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1369 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1368 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1366 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1360 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1356 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1347 | `mocha tests/test-*` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1343 | `istanbul cover _mocha test -- --timeout 20000` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1341 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1336 | `NODE_ENV=test mocha tests/*.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1335 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1335 | `standard && istanbul cover _mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1332 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1329 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1323 | `mocha --reporter dot` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1323 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1315 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1314 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1311 | `mocha -R spec ./test/unit/**` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1305 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1304 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1303 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1302 | `mocha spec/exec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1288 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1286 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1285 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1284 | `npm run lint && npm run mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1281 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1279 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1279 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1275 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1264 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1264 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1264 | `mocha --check-leaks --reporter spec --bail test/` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1260 | `mocha test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1260 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1259 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1257 | `mocha --recursive test/bin` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1255 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1249 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1243 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1242 | `npm run prepublishOnly && mocha test/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1232 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1228 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1223 | `istanbul test _mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1218 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1218 | `npm run lint && npm run mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1211 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1211 | `mocha --recursive test` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1211 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1207 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1207 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [normalize/mz](https://github.com/normalize/mz) | 1207 | `mocha --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1206 | `mocha --compilers js:babel-core/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1206 | `node ./node_modules/mocha/bin/mocha tests` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1200 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [variety/variety](https://github.com/variety/variety) | 1196 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1195 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1200 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [variety/variety](https://github.com/variety/variety) | 1196 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1195 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1188 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1183 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1176 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1174 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1174 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1171 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1169 | `webpack && npm run lint && npm run mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1166 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1149 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1146 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1145 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1143 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1133 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1128 | `mocha $(find test -name '*.test.js') --exit` | 
| [router5/router5](https://github.com/router5/router5) | 1127 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1125 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1124 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1122 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1121 | `istanbul cover _mocha test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1112 | `mocha --timeout 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1109 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1108 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1106 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1100 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1097 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1095 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1084 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1080 | `webpack && mocha test/unit` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1074 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 921 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 919 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 919 | `mocha test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 906 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 905 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 901 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 890 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 889 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 885 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1048 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1048 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1045 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1035 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1034 | `eslint src test && mocha --compilers babel-register` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1030 | `mocha test --compilers js:babel-core/register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1030 | `npm-run-all test:jest test:server:mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1029 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1029 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1025 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1023 | `mocha $(find test -name '*.test.js')` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 926 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 919 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 919 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 919 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 914 | `mocha test` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 905 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 978 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 977 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 976 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 973 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 972 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 966 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 961 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 955 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 950 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 950 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 949 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 946 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 946 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 946 | `mocha "client.test" --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 944 | `mocha --timeout 5000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 943 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 936 | `npm run lint && mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 926 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 926 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 921 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 919 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 919 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 919 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 914 | `mocha test` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 906 | `mocha -t 600000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 906 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 905 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 901 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 895 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 894 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 894 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 890 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 889 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 888 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 886 | `node_modules/.bin/mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 885 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 884 | `./node_modules/.bin/mocha --reporter spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 883 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 882 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 880 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 877 | `mocha --reporter list` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 872 | `istanbul cover -- _mocha --reporter spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 870 | `mocha --timeout 200000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 870 | `mocha test --compilers js:babel-register` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 870 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 869 | `nyc --check-coverage mocha test/*.test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 869 | `mocha --recursive ./test/*_spec.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 868 | `mocha -t 5000` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 867 | `npm run lint && npm run mocha:no-functional` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 865 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 865 | `standard && standard ./bin/* && mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 864 | `node_modules/.bin/mocha test/spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 849 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 848 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 847 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 845 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 842 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 837 | `npm run lint && mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 836 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 835 | `mocha test/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 835 | `nyc mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 833 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 828 | `mocha test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 827 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 825 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 823 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 820 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 817 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 817 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 817 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 820 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 817 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 817 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 817 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 810 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 807 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 795 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 794 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 792 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 791 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 791 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 790 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 790 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 787 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 783 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 780 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 780 | `./node_modules/.bin/mocha test/**/*` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 779 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 779 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 780 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 780 | `./node_modules/.bin/mocha test/**/*` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 779 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 779 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 776 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 773 | `mocha test` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 772 | `mocha -r should --reporter spec test/*.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 771 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 769 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 766 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 759 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 759 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 766 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 759 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 759 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 757 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 754 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 