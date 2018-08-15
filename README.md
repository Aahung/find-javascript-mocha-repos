# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:53 08/15/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43176 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41128 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39668 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30109 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25750 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24460 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23170 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19726 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18949 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16782 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16539 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15161 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14324 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13939 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13461 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13120 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12699 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12631 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12311 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12236 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11791 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11482 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11138 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11131 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10438 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10107 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10101 | `mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10096 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 10020 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9945 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9649 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9601 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9374 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9343 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9080 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9036 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8989 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8710 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8687 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8642 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8493 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8454 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8433 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8319 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8248 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8166 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8059 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7968 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7895 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7784 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7697 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7572 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7551 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7421 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7229 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7206 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7192 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7038 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7019 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6970 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6884 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6837 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6663 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6450 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6415 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6339 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6248 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6217 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6194 | `mocha test/test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6119 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5323 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5281 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5177 | `mocha src/**/*Tests.js --harmony` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5153 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5150 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5087 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4975 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4952 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4952 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4840 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4745 | `gulp build; mocha;` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5323 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5281 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5177 | `mocha src/**/*Tests.js --harmony` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5153 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5150 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5087 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4975 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4952 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4952 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4840 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4745 | `gulp build; mocha;` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4745 | `mocha test` | 
| [santinic/how2](https://github.com/santinic/how2) | 4734 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4732 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4730 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4694 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4615 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4543 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4464 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4433 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4421 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4420 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4402 | `npm run lint && npm run mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4402 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4136 | `mocha -R spec src` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 4135 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4095 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4067 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4022 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4012 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4007 | `mocha --require test/babel-hook test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3998 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3996 | `npm run lint ; mocha && mocha test/individual` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3894 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3881 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3865 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3849 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3833 | `mocha --check-leaks --reporter spec --bail` | 
| [erming/shout](https://github.com/erming/shout) | 3804 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [teambit/bit](https://github.com/teambit/bit) | 3788 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3781 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3777 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3747 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3669 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3658 | `npm run build && mocha test/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3655 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3616 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3595 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3550 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3542 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3524 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3520 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3508 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3461 | `node_modules/.bin/mocha test/lib/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3456 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3438 | `mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3405 | `NODE_ENV=test mocha --exit` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3394 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3343 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3242 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3240 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3242 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3240 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3234 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3220 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3176 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3170 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3140 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3129 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3117 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3064 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3060 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3059 | `mocha test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3048 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3045 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3044 | `mocha test/index.js && npm run demo` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3025 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3040 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3025 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3020 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3013 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2990 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2978 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2967 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2934 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2893 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2892 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2888 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2879 | `mocha -R spec --recursive src/test` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2878 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2869 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2864 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2850 | `mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2640 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2636 | `eslint . && mocha -t 5000` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2629 | `mocha test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2621 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2609 | `mocha-phantomjs ./test/index.html` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2609 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2606 | `npm run build && cd test && mocha . --reporter dot` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2588 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2568 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2535 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2523 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2513 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2512 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2503 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2469 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2447 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2445 | `mocha test/unit --require mochahook` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2445 | `mocha test/src/**/*.unit.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2703 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2673 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [json5/json5](https://github.com/json5/json5) | 2658 | `nyc --reporter=html --reporter=text mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2651 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2649 | `mocha --timeout 100000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2640 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2636 | `eslint . && mocha -t 5000` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2629 | `mocha test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2629 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2621 | `mocha --recursive --watch` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2614 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2609 | `mocha-phantomjs ./test/index.html` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2609 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2606 | `npm run build && cd test && mocha . --reporter dot` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2588 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2568 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2386 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2381 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2359 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2340 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2318 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2307 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2306 | `mocha test && npm run lint` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2282 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2281 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2266 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2251 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2381 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2359 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2350 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2340 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2318 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2307 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2306 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2300 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2282 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2281 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2266 | `mocha && eslint .` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2183 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2147 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2144 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2109 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2104 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2103 | `standard && mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2091 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2076 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2109 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2104 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2103 | `standard && mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2091 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2076 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2052 | `nyc npm run _mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2051 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2050 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2015 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1990 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1982 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1975 | `mocha --compilers js:babel-core/register __tests__` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1970 | `mocha && eslint *.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1970 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1968 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1964 | `mocha --require=test/test_helper.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1961 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1944 | `mocha --reporter spec --timeout 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 1943 | `npm run lint && npm run mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1938 | `./node_modules/.bin/mocha && npm run jshint` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1929 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1926 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1926 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1925 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [then/promise](https://github.com/then/promise) | 1918 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1912 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1912 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1912 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1887 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1878 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1866 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1827 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1810 | `mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1802 | `mocha && npm run lint` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1800 | `mocha test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1800 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1796 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1794 | `mocha test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1793 | `mocha tests --compilers js:babel-core/register` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1792 | `npm run lint && mocha --reporter spec test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1784 | `mocha --compilers js:babel-register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1780 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1779 | `mocha --reporter spec --grep .` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1735 | `mocha test -u bdd -R spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1727 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1724 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1705 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1697 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1693 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1689 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1686 | `mocha test --timeout 600000` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1680 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1673 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1667 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1663 | `mocha test/* --reporter spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1702 | `mocha ./test/basic.js -t 5000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1697 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1693 | `npm run lint && mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1689 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1686 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1680 | `mocha test/*.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1680 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1673 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1667 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1663 | `mocha test/* --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1651 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1643 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1643 | `mocha compiled_tests/` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1634 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1632 | `mocha --expose-gc --slow 300` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1627 | `mocha && size-limit` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1627 | `mocha tests/test.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1626 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1601 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1592 | `mocha test/setup.js test/spec/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1589 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1579 | `mocha test` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1531 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1527 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1526 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1523 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1515 | `nyc npm run mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1515 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1504 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1501 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1498 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1486 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1485 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1517 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1515 | `nyc npm run mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1515 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1504 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1501 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1498 | `nyc mocha` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1496 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [retejs/rete](https://github.com/retejs/rete) | 1486 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1485 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1454 | `nyc mocha --timeout=20000 test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1452 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1418 | `mocha --timeout 10000 ./tests/lib.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1309 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1304 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1300 | `mocha --reporter dot` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1285 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1282 | `NODE_ENV=test mocha tests/*.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1275 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1273 | `mocha --timeout 60000 test/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1266 | `mocha ./test/test*.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1264 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1263 | `mocha -R spec ./test/unit/**` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1262 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1259 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1255 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1251 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1251 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1249 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1248 | `npm run lint && npm run mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1244 | `mocha --check-leaks --reporter spec --bail test/` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1240 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1231 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1231 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1226 | `mocha --recursive test/bin` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1221 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1220 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1219 | `npm run prepublishOnly && mocha test/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1218 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1218 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1216 | `istanbul test _mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1207 | `npm run lint && npm run mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1201 | `node ./node_modules/mocha/bin/mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1201 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1200 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1195 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1190 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1188 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1188 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1187 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1187 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1182 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1182 | `mocha --recursive test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1169 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1163 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1155 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1152 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1152 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1146 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1145 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1135 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1132 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1135 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1132 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1131 | `webpack && npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1128 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1128 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1122 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1120 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1119 | `npm run lint && mocha --require @babel/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1119 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1114 | `istanbul cover _mocha test/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1114 | `npm run mocha:istanbul` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1110 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1107 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1081 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1076 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1075 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1075 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1071 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1067 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1064 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1059 | `mocha test/tests.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1056 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1054 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1071 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1067 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1064 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1059 | `mocha test/tests.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1056 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1054 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1046 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1046 | `mocha --reporter spec --bail --check-leaks test/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1043 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1043 | `standard && mocha -b` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1040 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1037 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1018 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1016 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1015 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1011 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1004 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1003 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1002 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 986 | `mocha -R list` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 984 | `npm run convertto:es5 && npm run mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 983 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 983 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 978 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 976 | `npm-run-all test:jest test:server:mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 970 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 964 | `mocha` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 970 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 964 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 954 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 952 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 951 | `mocha --recursive -r tests/setup tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 944 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 942 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 941 | `mocha --compilers js:babel-register test/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 940 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 936 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 928 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 927 | `npm run lint && mocha -R spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 926 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 916 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 915 | `mocha tests` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 911 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 910 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 909 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 904 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 901 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 896 | `mocha -t 600000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 889 | `mocha test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 888 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 887 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 886 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 885 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 884 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 879 | `nyc mocha specs` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 875 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 874 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 871 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 870 | `./node_modules/.bin/mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 842 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 841 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 841 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 840 | `mocha --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 840 | `mocha --recursive ./test/*_spec.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 840 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 838 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 837 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 821 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 818 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 815 | `mocha test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 814 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 812 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 812 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 842 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 841 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 841 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 840 | `mocha --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 840 | `mocha --recursive ./test/*_spec.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 840 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 838 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 837 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 836 | `mocha --reporter list` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 832 | `npm run lint && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 830 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 830 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 821 | `mocha test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 821 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 818 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 815 | `mocha test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 814 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 813 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 812 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 812 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 809 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 780 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 768 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 766 | `mocha --no-timeouts` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 759 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 758 | `mocha --recursive -s 15 test/` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 758 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 758 | `./node_modules/.bin/mocha test/**/*` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 786 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 786 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 784 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 784 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 783 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 782 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 781 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 780 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 774 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 770 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 774 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 770 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 768 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 766 | `mocha --no-timeouts` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 761 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 759 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 758 | `mocha --recursive -s 15 test/` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 758 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 758 | `./node_modules/.bin/mocha test/**/*` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 755 | `mocha -r should --reporter spec test/*.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 752 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 745 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 744 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 742 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 742 | `mocha --exit --use_strict src/*.test.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 741 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 740 | `npm run lint && npm run mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 739 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 738 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 729 | `mocha test.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 728 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 728 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 727 | `babel-node node_modules/.bin/_mocha -- test` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 725 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 724 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 724 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 723 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 723 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 720 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 720 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 717 | `mocha --reporter spec build/test/index.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 716 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 