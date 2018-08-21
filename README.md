# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:03 08/21/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43253 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41166 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39765 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30145 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25908 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24492 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23235 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19808 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18997 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17066 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16816 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16595 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15225 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14339 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13979 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13522 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13154 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12731 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12646 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12329 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11833 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11503 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11214 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11178 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10473 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10168 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10124 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10117 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10040 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9965 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9701 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9645 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9701 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9645 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9389 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9373 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9125 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9080 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9003 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8730 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8716 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8681 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8500 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8470 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8442 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8323 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8312 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8176 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8066 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8007 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7902 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7840 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7715 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7618 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7554 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7427 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7247 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7227 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7223 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7056 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7049 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7008 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6892 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6886 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6700 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6479 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6467 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6387 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6262 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6234 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6229 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6222 | `npm run test:mocha:src` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4754 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4742 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4742 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4733 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4695 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4630 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4581 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4573 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4470 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4443 | `mocha --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4436 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4435 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4409 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4330 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5344 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5307 | `standard && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5251 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5216 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5179 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5148 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5090 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5010 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4979 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4970 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4932 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4842 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4762 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4754 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4742 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4742 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4733 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4695 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4630 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4581 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4573 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4470 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4443 | `mocha --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4436 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4435 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4423 | `npm run lint && npm run mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4409 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4330 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4214 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4197 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4162 | `mocha -R spec src` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4146 | `nyc mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4130 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4079 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4023 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4022 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4012 | `mocha --require test/babel-hook test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4012 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4011 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3979 | `mocha --require should --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3929 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3895 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3879 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3857 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3843 | `mocha --check-leaks --reporter spec --bail` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3818 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3818 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3816 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3806 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3755 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3676 | `nyc mocha "test/**/*.test.js"` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3670 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3663 | `npm run build && mocha test/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3629 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3626 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3552 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3545 | `mocha --reporter spec --timeout 3000` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3530 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3527 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3525 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3468 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3465 | `node_modules/.bin/mocha test/lib/` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3459 | `NODE_ENV=test mocha test/**/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3449 | `NODE_ENV=test mocha --exit` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3250 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3250 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3227 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3195 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3173 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3165 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3144 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3128 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3127 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3097 | `mocha test/*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3066 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3056 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3056 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3054 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3053 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3195 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3173 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3165 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3144 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3145 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3128 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3127 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3097 | `mocha test/*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3077 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3066 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3056 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3056 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3054 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3053 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3034 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3027 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3018 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3000 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2998 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2825 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2812 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2780 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2777 | `mocha -R spec spec spec/reporters` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2765 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2764 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2740 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2726 | `mocha --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2722 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2709 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2683 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2679 | `eslint . && mocha -t 5000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2658 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2653 | `mocha test.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2647 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2814 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [github-tools/github](https://github.com/github-tools/github) | 2812 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2780 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2777 | `mocha -R spec spec spec/reporters` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2765 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2764 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2740 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2726 | `mocha --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2722 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2709 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2683 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2679 | `eslint . && mocha -t 5000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2658 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2653 | `mocha test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2652 | `mocha --timeout 100000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2647 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2633 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2628 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2624 | `mocha --recursive --watch` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2617 | `npm run build && cd test && mocha . --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2616 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2610 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2596 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2570 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2546 | `nyc mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2543 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2538 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2521 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2515 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2476 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2463 | `mocha test` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2453 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2451 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2450 | `mocha test/src/**/*.unit.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2448 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2437 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2425 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2409 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2396 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2385 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2374 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2347 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2323 | `mocha -R spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2318 | `mocha test && npm run lint` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2310 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2308 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2284 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2275 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2255 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2229 | `mocha test/ --no-timeouts` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2059 | `nyc npm run _mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2057 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2051 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2044 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1987 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1975 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1970 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1965 | `mocha --require=test/test_helper.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1963 | `npm run lint && npm run mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1947 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1942 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1931 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1930 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1927 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [then/promise](https://github.com/then/promise) | 1922 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1919 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1918 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1915 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1892 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1886 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1869 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1853 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1842 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1840 | `npm run mocha && npm run karma` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1839 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1838 | `mocha --reporter spec && npm run test-typescript` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1817 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1814 | `mocha --reporter spec test/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1807 | `mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1805 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1786 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1785 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1770 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1764 | `mocha test/**/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1746 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1739 | `mocha test -u bdd -R spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1726 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1712 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1710 | `mocha ./test/basic.js -t 5000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1708 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1693 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1692 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1688 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1688 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1683 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1677 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1673 | `npm run lint && npm run mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1669 | `mocha test/* --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1654 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1653 | `mocha compiled_tests/` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1654 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1653 | `mocha compiled_tests/` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1649 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1641 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1639 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1638 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1632 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1629 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1627 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1604 | `mocha test` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1603 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1601 | `mocha test/setup.js test/spec/*.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1591 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1580 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1573 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1571 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1570 | `./node_modules/mocha/bin/mocha -R spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1565 | `standard "./src/*.js" && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1562 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1551 | `./node_modules/.bin/mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1546 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1503 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1501 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1497 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1487 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1484 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1464 | `nyc mocha --timeout=20000 test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1454 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1487 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1484 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1464 | `nyc mocha --timeout=20000 test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1454 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1424 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1413 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1413 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1412 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1399 | `mocha --check-leaks --require @babel/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1388 | `istanbul cover _mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1385 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1384 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1277 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1277 | `mocha -R spec ./test/unit/**` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1275 | `mocha --timeout 60000 test/` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1274 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1264 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1262 | `npm run lint && npm run mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1257 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1256 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1252 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1252 | `mocha --check-leaks --reporter spec --bail test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1252 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1250 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1247 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1242 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1236 | `mocha --recursive test/bin` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1235 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1228 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1226 | `npm run prepublishOnly && mocha test/test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1226 | `npm run prepublishOnly && mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1225 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1224 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1222 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1217 | `istanbul test _mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1212 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1209 | `npm run lint && npm run mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1203 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1203 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1203 | `mocha --reporter spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1201 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1194 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1193 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1192 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1192 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [variety/variety](https://github.com/variety/variety) | 1190 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1189 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1187 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1187 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1184 | `mocha --compilers js:babel-core/register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1181 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1171 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1163 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1161 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1146 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1145 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1142 | `webpack && npm run lint && npm run mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1141 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1140 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1136 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1134 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1131 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1129 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1125 | `mocha $(find test -name '*.test.js')` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1123 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1119 | `xo && mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1118 | `npm run mocha:istanbul` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1118 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1115 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1118 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1115 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [router5/router5](https://github.com/router5/router5) | 1114 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1106 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1106 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1105 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1099 | `mocha --timeout 20000` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1095 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1091 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1084 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1083 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1059 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1058 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1052 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1051 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1049 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1047 | `standard && mocha -b` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1039 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1029 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1023 | `eslint src test && mocha --compilers babel-register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1043 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1039 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1037 | `mocha --timeout 30000 --recursive ./tests` | 
| [electron/spectron](https://github.com/electron/spectron) | 1029 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1023 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1022 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1022 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1020 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1018 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1011 | `mocha --recursive test/unit/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 989 | `npm run convertto:es5 && npm run mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 987 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 980 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 978 | `npm-run-all test:jest test:server:mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 974 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 973 | `mocha` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 971 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 980 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 978 | `npm-run-all test:jest test:server:mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 974 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 973 | `mocha` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 971 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 957 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 956 | `mocha --recursive -r tests/setup tests` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 955 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 925 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 918 | `mocha tests` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 914 | `mocha ./test/index.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 913 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 913 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 908 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 903 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 903 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 898 | `mocha -t 600000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 894 | `mocha test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 889 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 888 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 886 | `node_modules/.bin/mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 885 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 881 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 881 | `nyc mocha specs` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 881 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 881 | `nyc mocha specs` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 878 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 876 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 876 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 873 | `./node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 869 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 868 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 866 | `istanbul cover -- _mocha --reporter spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 865 | `mocha -t 5000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 862 | `node_modules/.bin/mocha test/spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 858 | `standard && standard ./bin/* && mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 857 | `mocha test --compilers js:babel-register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 856 | `nyc --check-coverage mocha test/*.test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 855 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 852 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 849 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 847 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 845 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 844 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 842 | `mocha --reporter spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 841 | `mocha --reporter list` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 841 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 838 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 838 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 837 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 835 | `npm run lint && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 833 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 831 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 822 | `mocha test/index.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 820 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 818 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 817 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 815 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 814 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 814 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 814 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 813 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 811 | `mocha --async-only` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 806 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 802 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 800 | `mocha --harmony --full-trace --check-leaks` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 799 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 798 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 797 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 792 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 791 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 790 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 789 | `npm run mocha-test test/integration` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 788 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 788 | `npm run build && istanbul test _mocha test/test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 788 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 787 | `mocha --colors --reporter spec test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 787 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 771 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 770 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 767 | `mocha --no-timeouts` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 763 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 761 | `mocha -r should --reporter spec test/*.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 761 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 761 | `./node_modules/.bin/mocha test/**/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 760 | `mocha --recursive -s 15 test/` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 755 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 761 | `mocha -r should --reporter spec test/*.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 761 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 761 | `./node_modules/.bin/mocha test/**/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 760 | `mocha --recursive -s 15 test/` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 755 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 753 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 749 | `mocha --exit --use_strict src/*.test.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 747 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 746 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 745 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 735 | `mocha tests/*.mocha.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 732 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 732 | `babel-node node_modules/.bin/_mocha -- test` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 730 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 728 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 727 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 726 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 724 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 724 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 723 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 723 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 732 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 732 | `babel-node node_modules/.bin/_mocha -- test` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 730 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 728 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 727 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 726 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 724 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 724 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 723 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 723 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 713 | `./bin/selenium-standalone install && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 708 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 707 | `mocha ./test/index.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 705 | `mocha ./test/test.js --timeout 1000000` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 702 | `mocha` | 