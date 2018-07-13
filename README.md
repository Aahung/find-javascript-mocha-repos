# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:10 07/13/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42685 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40942 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39207 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29865 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24295 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24293 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23839 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22780 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19382 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18701 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16568 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16266 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14820 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14243 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13735 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13057 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12954 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12571 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12538 | `./node_modules/.bin/mocha test/` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12459 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12215 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12204 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11515 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11327 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10859 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10827 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10225 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9923 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 9921 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9899 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9880 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9844 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9290 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9271 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9071 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8939 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8904 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8792 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8521 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8462 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8439 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8404 | `mocha --check-leaks -R dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8364 | `mocha tests/*.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8344 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8257 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8110 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8012 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7848 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7820 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7811 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7607 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7538 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7483 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7441 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7376 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7327 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 7097 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7067 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7045 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6934 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6858 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6851 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6834 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6601 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6345 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6182 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6172 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6125 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6082 | `mocha; jshint *.js lib` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6043 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6011 | `mocha test/test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5203 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5172 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5156 | `mocha --color` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5137 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5016 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4924 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4833 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4827 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4813 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4810 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4702 | `gulp build; mocha;` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4687 | `mocha --reporter spec -t 8000` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4126 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4034 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4027 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3989 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3942 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3940 | `mocha --require should --reporter spec` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3921 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3904 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3888 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3803 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3942 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3940 | `mocha --require should --reporter spec` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3939 | `npm run lint ; mocha && mocha test/individual` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3921 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3904 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3888 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3803 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3728 | `mocha --check-leaks --reporter spec --bail` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3720 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3699 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3649 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3617 | `npm run build && mocha test/*.test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3728 | `mocha --check-leaks --reporter spec --bail` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3720 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3699 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3668 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3649 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3617 | `npm run build && mocha test/*.test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3599 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3579 | `nyc mocha "test/**/*.test.js"` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3573 | `mocha tests/javascript` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3562 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 3538 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3521 | `mocha --reporter spec --timeout 3000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3518 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3515 | `node_modules/.bin/mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 3500 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3496 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3465 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3454 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3433 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3417 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3401 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3365 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3332 | `NODE_ENV=test mocha test/**/*.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3237 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3228 | `NODE_ENV=test mocha --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3173 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3159 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3157 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3149 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3134 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3133 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3133 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3123 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3085 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3065 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3053 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3020 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3017 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3008 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2990 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2983 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2979 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2978 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2934 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2888 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2873 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2867 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2862 | `mocha -R spec --recursive src/test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2859 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2855 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2853 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2847 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2825 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2815 | `istanbul cover _mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2806 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2798 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2796 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2790 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2785 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2763 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2785 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2763 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2749 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2717 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2716 | `mocha test-node` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2705 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2695 | `xo && mocha` | 
| [css/csso](https://github.com/css/csso) | 2693 | `mocha --reporter dot` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2684 | `mocha -R landing test/index` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2681 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2636 | `mocha --timeout 100000` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2619 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2636 | `mocha --timeout 100000` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2619 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [mde/ejs](https://github.com/mde/ejs) | 2615 | `mocha --require should --reporter spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2614 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2605 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2604 | `mocha-phantomjs ./test/index.html` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2603 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2582 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2572 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2566 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2558 | `nyc --reporter=html --reporter=text mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2554 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2547 | `npm run build && cd test && mocha . --reporter dot` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2529 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2511 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2489 | `nyc mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2466 | `mocha --reporter=spec test/*-test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2466 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2464 | `mocha "test/**/*-test.js"` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2437 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2432 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2425 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2417 | `mocha test/src/**/*.unit.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2414 | `eslint . && mocha -t 5000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2405 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2401 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2400 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2391 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2375 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2369 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2344 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2342 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2335 | `nyc --reporter=html --reporter=text mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2324 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2294 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2289 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2270 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2265 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2251 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2248 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2231 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2218 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2218 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2208 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2207 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2153 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2130 | `cross-env BABEL_ENV=test mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2130 | `mocha --compilers js:babel-register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2112 | `mocha test/ --no-timeouts` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2103 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2094 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2083 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2062 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2060 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2042 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2021 | `mocha test/runner.js --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2008 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2004 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1997 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1865 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1857 | `mocha test/*.test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1850 | `npm run lint && npm run mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1845 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1839 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1827 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1817 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1799 | `npm run mocha && npm run karma` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1792 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1785 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1767 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1765 | `mocha && npm run lint` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1759 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1759 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1758 | `mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1751 | `mocha --reporter spec --grep .` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1745 | `mocha tests --compilers js:babel-core/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1741 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1738 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1723 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1722 | `mocha test/**/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1721 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1715 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1708 | `mocha test -u bdd -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1706 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1704 | `mocha --compilers js:babel-register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1697 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1696 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1677 | `npm run lint && mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1671 | `mocha test --timeout 600000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1667 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1667 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1660 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1657 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1649 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1641 | `npm run lint && npm run mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1641 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1630 | `mocha spec` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1630 | `mocha test/* --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1625 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1621 | `mocha && size-limit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1615 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1594 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1593 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1545 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1538 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1537 | `mocha --reporter spec` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1536 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1533 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1529 | `mocha tests.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1527 | `mocha test/setup.js test/spec/*.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1521 | `standard "./src/*.js" && mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1517 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1497 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1497 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1492 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1491 | `mocha --check-leaks --reporter spec --bail` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1489 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1517 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1497 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1497 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1497 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1492 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1492 | `mocha -u tdd` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1491 | `mocha --check-leaks --reporter spec --bail` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1489 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1485 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1483 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1480 | `mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1477 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1475 | `mocha test` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1472 | `nyc npm run mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1351 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1336 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1320 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1316 | `mocha --opts test/opts/mocha.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1311 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1311 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1310 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1309 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1306 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1305 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1304 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1301 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1398 | `mocha --timeout 10000 ./tests/lib.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1393 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1390 | `nyc mocha --timeout=20000 test.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1386 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1382 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1377 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1374 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1357 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1351 | `npm run build && mocha -r should` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1349 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1346 | `mocha --check-leaks --require @babel/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1343 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1336 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1332 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1323 | `mocha test/unit` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1320 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1316 | `mocha --opts test/opts/mocha.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1311 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1311 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1310 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1213 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1204 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1202 | `NODE_ENV=test mocha tests/*.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1198 | `mocha --check-leaks --reporter spec --bail test/` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1197 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1195 | `mocha -R spec ./test/unit/**` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1195 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1194 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1192 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1187 | `mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1181 | `npm run lint && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1180 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1177 | `mocha --recursive test/bin` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1258 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1256 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1249 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1249 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1247 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1239 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1239 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1237 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1236 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1232 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1231 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1219 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1213 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1206 | `mocha src/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1205 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1204 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1198 | `mocha --check-leaks --reporter spec --bail test/` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1197 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1195 | `mocha -R spec ./test/unit/**` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1195 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1194 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1193 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1192 | `mocha test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1191 | `mocha ./test/test*.js --reporter spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1187 | `mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1181 | `npm run lint && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1180 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1177 | `mocha --recursive test/bin` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1173 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1169 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1166 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1164 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1163 | `npm run prepublishOnly && mocha test/test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1161 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1160 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1159 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1149 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1148 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1139 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1134 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1139 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1134 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1131 | `mocha --compilers js:babel-core/register` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1114 | `mocha $(find test -name '*.test.js')` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1113 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1110 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1106 | `xo && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1104 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1103 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1102 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1100 | `istanbul cover _mocha test/*.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1097 | `mocha test/*` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1096 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1093 | `NODE_PATH=. mocha **/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1093 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1092 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1084 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1080 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1078 | `mocha --compilers js:babel-register` | 
| [router5/router5](https://github.com/router5/router5) | 1078 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1071 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1069 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1069 | `webpack && npm run lint && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1066 | `npm run lint && mocha --require @babel/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1065 | `istanbul test _mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1065 | `standard && mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1064 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1062 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1052 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [electron/asar](https://github.com/electron/asar) | 1049 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1047 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1045 | `mocha test/tests.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1040 | `npm run mocha:istanbul` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1039 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1039 | `webpack && mocha test/unit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1037 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1036 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1026 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1023 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1019 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1019 | `mocha --reporter spec --bail --check-leaks test/` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1018 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1017 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1017 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1017 | `mocha --timeout 20000` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [electron/spectron](https://github.com/electron/spectron) | 1011 | `mocha && standard` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1009 | `mocha $(find test -name '*.test.js')` | 
| [tomas/needle](https://github.com/tomas/needle) | 1007 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1006 | `eslint src test && mocha --compilers babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1000 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 997 | `mocha --recursive test/unit/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 990 | `mocha --async-only` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 988 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 983 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 979 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 978 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 955 | `npm-run-all test:jest test:server:mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 951 | `mocha --timeout 30000 --recursive ./tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 938 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 929 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 938 | `mocha "client.test" --compilers js:babel-register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 929 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 925 | `mocha --reporter spec --bail --check-leaks test/` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 925 | `mocha -R spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 921 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 918 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 916 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 889 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 886 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 884 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 883 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 879 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 879 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 877 | `mocha -t 600000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 876 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 872 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 868 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 864 | `mocha --timeout 200000` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 863 | `nyc mocha specs` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 863 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 863 | `nyc mocha specs` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 863 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 855 | `eslint test && mocha --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 855 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 854 | `node_modules/.bin/mocha test/spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 851 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 851 | `mocha -t 5000` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 850 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 849 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 847 | `standard && standard ./bin/* && mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 845 | `./node_modules/.bin/mocha -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 845 | `mocha test --compilers js:babel-register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 844 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 841 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 840 | `./node_modules/.bin/mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 839 | `istanbul cover -- _mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 833 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 831 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 823 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 823 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 819 | `mocha --reporter list` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 819 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 816 | `npm run lint && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 816 | `npm run lint && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 808 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 806 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 806 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 805 | `nyc --check-coverage mocha test/*.test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 803 | `mocha test/index.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 803 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 802 | `cake build && mocha ./test/mocha/*.coffee` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 801 | `mocha --recursive ./test/*_spec.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 798 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 797 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 796 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 794 | `mocha test` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 793 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 792 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 786 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 784 | `mocha --colors --reporter spec test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 784 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 780 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 786 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 784 | `mocha --colors --reporter spec test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 784 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 781 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 781 | `mocha --harmony --full-trace --check-leaks` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 780 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 776 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 776 | `npm run build && istanbul test _mocha test/test.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 775 | `xo && mocha -R spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 775 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 774 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 773 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 771 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 769 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 768 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 767 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 767 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 766 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 764 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 762 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 762 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 755 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 752 | `mocha --recursive -s 15 test/` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 752 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 749 | `mocha --no-timeouts` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 749 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 749 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 747 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 747 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 739 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 739 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 739 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 735 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 734 | `mocha test` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 732 | `mocha -r should --reporter spec test/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 732 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 730 | `npm run lint && npm run mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 730 | `mocha test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 728 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 725 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 724 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 724 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [scality/S3](https://github.com/scality/S3) | 721 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 719 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 718 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 718 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 717 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 716 | `npm run bundle && mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 716 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 716 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 715 | `babel-node node_modules/.bin/_mocha -- test` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 711 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 708 | `nyc mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 704 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 697 | `npm run-script jshint && npm run-script mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 693 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 692 | `mocha --reporter spec` | 
| [miukimiu/react-kawaii](https://github.com/miukimiu/react-kawaii) | 689 | `./node_modules/mocha/bin/mocha --compilers js:babel-register,css:nullCompiler.js  ./test/**/*.spec.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 689 | `mocha ./test/test.js --timeout 1000000` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 685 | `mocha` | 