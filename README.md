# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:58 06/11/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42055 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40706 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38712 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29657 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24106 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23443 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 23022 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22416 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19047 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18460 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16330 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15945 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14438 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14155 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13509 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12767 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12505 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12475 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12346 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12155 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12107 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11920 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11167 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11069 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10612 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10481 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10018 | `mocha test/index.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9740 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9739 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9724 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9701 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9471 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9166 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9003 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8852 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8803 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8798 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8523 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8394 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8364 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8306 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8244 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8226 | `grunt clean:test && mocha --exit` | 
| [amark/gun](https://github.com/amark/gun) | 8184 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8059 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8027 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7951 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7794 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7749 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7616 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7606 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7523 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7514 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7342 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7090 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7089 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6902 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6897 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6896 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6831 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6786 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6727 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6632 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6318 | `npm run lint -s && npm run mocha -s` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6208 | `mocha test node-test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6178 | `npm run build-cli && mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6177 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6139 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6113 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5900 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5854 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5850 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5737 | `mocha; jshint *.js lib` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5731 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5635 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5605 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5536 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5396 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5380 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5294 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5279 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5161 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5125 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4983 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4978 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4938 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4897 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4822 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4719 | `mocha test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4697 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4697 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4672 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4659 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4649 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4606 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3127 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3108 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3100 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3057 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3027 | `NODE_ENV=test mocha --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3006 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2997 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2981 | `mocha test/*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2962 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2959 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2949 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2909 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2908 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2890 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2876 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2872 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2848 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2843 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3695 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3660 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3620 | `standard && mocha --timeout 60000 test/test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3616 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3594 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3561 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3507 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3501 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3484 | `node_modules/.bin/mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3468 | `nyc mocha "test/**/*.test.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3466 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3446 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3432 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3425 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3415 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3414 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3377 | `node_modules/.bin/mocha test/tests.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3376 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3366 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3292 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3127 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3127 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3127 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3127 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3108 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3100 | `nyc mocha && tsc` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3079 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3057 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3051 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3027 | `NODE_ENV=test mocha --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3006 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2997 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2981 | `mocha test/*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2962 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2959 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2949 | `mocha test/index.js && npm run demo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2959 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2949 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2909 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2908 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2890 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2876 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2872 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2848 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2843 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2841 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2837 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2814 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2791 | `istanbul cover _mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2782 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2777 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2704 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2704 | `npm run mocha && npm run lint` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2676 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2673 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2662 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2626 | `mocha --timeout 100000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2618 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2602 | `node_modules/.bin/mocha --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2566 | `mocha -R landing test/index` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2559 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2555 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2547 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2540 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2626 | `mocha --timeout 100000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2618 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2602 | `node_modules/.bin/mocha --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2566 | `mocha -R landing test/index` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2559 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2555 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2547 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2540 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2510 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2496 | `npm run build && cd test && mocha . --reporter dot` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2074 | `mocha --compilers js:babel-register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2050 | `mocha test/index.js --reporter dot` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2042 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 2027 | `mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2018 | `mocha test/ --no-timeouts` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1984 | `mocha test/runner.js --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 1978 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1975 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1949 | `mocha --require=test/test_helper.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1927 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2195 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2186 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2184 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2168 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2160 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2128 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2110 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2090 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2085 | `mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2018 | `mocha test/ --no-timeouts` | 
| [slate/slate](https://github.com/slate/slate) | 2009 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1984 | `mocha test/runner.js --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 1978 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1975 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1973 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1958 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1949 | `mocha --require=test/test_helper.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1927 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1923 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1914 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1909 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1927 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1923 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1914 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1914 | `mocha --compilers js:babel-core/register __tests__` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1912 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1909 | `mocha --reporter spec --timeout 5000` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1903 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1884 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1884 | `nyc npm run _mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1883 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1871 | `mocha && eslint *.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1927 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1923 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1914 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1914 | `mocha --compilers js:babel-core/register __tests__` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1912 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1909 | `mocha --reporter spec --timeout 5000` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1903 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1884 | `nyc npm run _mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1883 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1871 | `mocha && eslint *.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1865 | `mocha tests.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1863 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1860 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [then/promise](https://github.com/then/promise) | 1860 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1853 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1839 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1830 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1824 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1815 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1808 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1803 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1800 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1788 | `mocha --reporter spec && npm run test-typescript` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1785 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1781 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1779 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1769 | `mocha -R spec spec spec/reporters` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1769 | `npm run mocha && npm run karma` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1769 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1747 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1729 | `mocha && npm run lint` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1722 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1717 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1714 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1713 | `mocha --reporter spec test/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1713 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1709 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1706 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1704 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1704 | `npm run lint && mocha test/unit --recursive && mocha test/runner --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1701 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1689 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1677 | `mocha test/**/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1664 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1663 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1654 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1651 | `mocha test --timeout 600000` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1640 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1640 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1637 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1606 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1603 | `mocha test/* --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1554 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1550 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1501 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1492 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1491 | `standard "./src/*.js" && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1482 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1476 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1473 | `mocha -R spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1473 | `mocha test/setup.js test/spec/*.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1470 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1468 | `nyc mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1462 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1462 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1461 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1396 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1386 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1372 | `mocha test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1371 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1360 | `mocha -R spec test/*.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1351 | `cross-env NODE_ENV=test nyc mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1461 | `mocha test/**/*.spec.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1454 | `mocha --check-leaks --reporter spec --bail` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1444 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1440 | `nyc npm run mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1440 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1435 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1433 | `mocha --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1316 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1313 | `nyc mocha --timeout=20000 test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1305 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1304 | `mocha --check-leaks --require @babel/register` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1299 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1294 | `istanbul cover _mocha test -- --timeout 20000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1292 | `./node_modules/.bin/mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1286 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1283 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1281 | `mocha spec/exec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1274 | `mocha --opts test/opts/mocha.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1274 | `mocha test/unit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1257 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1256 | `eslint src && mocha && karma start --single-run` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1254 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1253 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1246 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1244 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1242 | `mocha --timeout 60000 test/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1238 | `mocha test/*.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1236 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1235 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1232 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1232 | `standard && istanbul cover _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1228 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1226 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1224 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1223 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1214 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1299 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1294 | `istanbul cover _mocha test -- --timeout 20000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1292 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1286 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1286 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1283 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1281 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1281 | `mocha spec/exec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1274 | `mocha --opts test/opts/mocha.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1274 | `mocha test/unit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1257 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1256 | `eslint src && mocha && karma start --single-run` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1254 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1246 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1244 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1238 | `mocha test/*.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1236 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1235 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1232 | `standard && istanbul cover _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1226 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1224 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1223 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1214 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1211 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1202 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1197 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1187 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1187 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1183 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1181 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1173 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [normalize/mz](https://github.com/normalize/mz) | 1172 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1171 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1164 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1146 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1143 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1141 | `mocha -R spec ./test/unit/**` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1138 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1135 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1131 | `mocha ./test/test*.js --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1130 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1146 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1143 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1141 | `mocha -R spec ./test/unit/**` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1136 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1135 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1131 | `mocha ./test/test*.js --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1130 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1129 | `NODE_ENV=test mocha tests/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1122 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1119 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1119 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1117 | `npm run prepublishOnly && mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1115 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1114 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 932 | `npm run convertto:es5 && npm run mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 909 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 907 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 905 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 891 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 993 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 986 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 974 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 973 | `eslint src test && mocha --compilers babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 970 | `npm run mocha:istanbul` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 964 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 963 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 961 | `mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 932 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 928 | `mocha "client.test" --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 912 | `mocha --compilers js:babel-register test/*.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 911 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 909 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 905 | `npm run lint && mocha -R spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1026 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1023 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1018 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [electron/asar](https://github.com/electron/asar) | 1018 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1016 | `webpack && mocha test/unit` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1013 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1007 | `npm run lint && mocha --require @babel/register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1007 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1004 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1004 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1001 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 918 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 912 | `mocha --compilers js:babel-register test/*.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 754 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 754 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 744 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 733 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 733 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 733 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 732 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 732 | `mocha --reporter spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 918 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 912 | `mocha --compilers js:babel-register test/*.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 911 | `mocha ./test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 910 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 909 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 907 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 905 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 902 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 901 | `mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 883 | `mocha tests` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 870 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 869 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 865 | `mocha -t 600000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 861 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 860 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha:no-functional` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 858 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 853 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 849 | `mocha spec/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 853 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 852 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 849 | `mocha spec/*.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 839 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 839 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 839 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 838 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 838 | `mocha -t 5000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 835 | `mocha test --compilers js:babel-core/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 833 | `nyc mocha specs` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 826 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 825 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 822 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 820 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 820 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 816 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 809 | `mocha --reporter spec --bail --check-leaks test/` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 809 | `mocha --reporter spec --bail --check-leaks test/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 808 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 804 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 803 | `./node_modules/.bin/mocha --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 801 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 799 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 797 | `mocha --timeout 30000 --recursive ./tests` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 797 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 797 | `mocha test` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 782 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 779 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 776 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 774 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 769 | `mocha test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 766 | `npm run mocha-test test/integration` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 766 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 776 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 774 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 771 | `nyc --check-coverage mocha test/*.test.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 769 | `mocha test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 766 | `npm run mocha-test test/integration` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 766 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 766 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 765 | `mocha --recursive ./test/*_spec.js` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 763 | `nyc npm run mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 763 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 761 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 761 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 754 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 754 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 747 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 747 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 744 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 744 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 743 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 733 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 733 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 733 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 732 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 732 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 732 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 729 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 726 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 725 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 724 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 723 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 723 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 721 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 726 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 725 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 724 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 723 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 723 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 721 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 721 | `npm run lint && npm run mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 718 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 715 | `npm run bundle && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 714 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 