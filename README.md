# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:14 06/04/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41898 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40657 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38604 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29614 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24079 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23359 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22699 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22323 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18972 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18406 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16299 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15888 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14375 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14123 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13468 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12732 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12480 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12314 | `./node_modules/.bin/mocha test/` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12300 | `mocha --reporter spec` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12150 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12086 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11850 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11139 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10999 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10547 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10404 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9975 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9715 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9708 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9686 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9661 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9163 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9163 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8933 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8839 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8776 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8733 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8467 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8372 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8334 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8295 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8221 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8211 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8164 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8022 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8017 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7936 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7746 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7737 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7599 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7564 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7515 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7498 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7332 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7067 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7031 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6874 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6867 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6860 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6807 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6778 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6698 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6600 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6306 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6140 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6123 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6109 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6094 | `npm run build-cli && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6025 | `mocha test node-test --recursive` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5859 | `mocha --exit --require babel-core/register` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5833 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5832 | `mocha test/test.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4490 | `mocha test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4417 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4354 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4322 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4214 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4206 | `mocha --recursive && make test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4099 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4092 | `npm run lint && npm run mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5072 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4946 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4933 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4924 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4897 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4815 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4718 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4696 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4674 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4673 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4650 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4613 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4594 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3122 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3086 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3080 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3060 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3038 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2998 | `NODE_ENV=test mocha --exit` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2990 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2977 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2976 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2953 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2939 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2936 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2891 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2891 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2873 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2864 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2853 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2845 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2838 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2838 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4171 | `nyc mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4099 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4092 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3971 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3935 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3911 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3899 | `mocha --require should --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3859 | `npm run lint ; mocha && mocha test/individual` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3856 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3799 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3784 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 584 | `mocha --compilers js:babel-register` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 573 | `xo && mocha` | 
| [jmar777/suspend](https://github.com/jmar777/suspend) | 558 | `node ./node_modules/mocha/bin/mocha --harmony --reporter list` | 
| [matthewmueller/socrates](https://github.com/matthewmueller/socrates) | 557 | `devtool node_modules/mocha/bin/_mocha -qc -- ./test/` | 
| [techlayer/espresso.js](https://github.com/techlayer/espresso.js) | 521 | `mocha` | 
| [eugeneware/debowerify](https://github.com/eugeneware/debowerify) | 513 | `node_modules/.bin/mocha` | 
| [deprecate/generator-ember](https://github.com/deprecate/generator-ember) | 473 | `mocha --reporter spec` | 
| [contra/smog](https://github.com/contra/smog) | 450 | `mocha --compilers coffee:coffee-script` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3465 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3449 | `nyc mocha "test/**/*.test.js"` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3430 | `node_modules/.bin/mocha test/lib/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3427 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3401 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3376 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3352 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3343 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3332 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3273 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3259 | `node_modules/.bin/mocha test/tests.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3190 | `NODE_ENV=test mocha test/**/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3122 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3117 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3115 | `./node_modules/.bin/mocha test/test.*.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3086 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3080 | `nyc mocha && tsc` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3077 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3060 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3038 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3031 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3005 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2998 | `NODE_ENV=test mocha --exit` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2990 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2977 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2976 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2953 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2939 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2936 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2891 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2891 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2873 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2864 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2853 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2845 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2840 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2838 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2838 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [json5/json5](https://github.com/json5/json5) | 2450 | `nyc --reporter=html --reporter=text mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2444 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2426 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2407 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2403 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2401 | `mocha test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2389 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2374 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2355 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2352 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2347 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2297 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2297 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2286 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2251 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2243 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2237 | `nyc --reporter=html --reporter=text mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2655 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2623 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2594 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2585 | `node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2556 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2543 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2542 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2540 | `mocha -R landing test/index` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2527 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2505 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2196 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2169 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2167 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2152 | `mocha && eslint .` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2146 | `eslint . && mocha -t 5000` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2145 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2114 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2107 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2088 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2084 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1687 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1668 | `mocha test/**/*.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1652 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1640 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1638 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1636 | `mocha ./test/basic.js -t 5000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1635 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1617 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1593 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1592 | `mocha test/* --reporter spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1527 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1501 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1496 | `eslint --cache . && tsc && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1481 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1480 | `mocha -u tdd` | 
| [zeit/ms](https://github.com/zeit/ms) | 1476 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1473 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1467 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1466 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1464 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [samccone/drool](https://github.com/samccone/drool) | 1450 | `mocha test/tests.js --timeout=10000` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1449 | `mocha --check-leaks --reporter spec --bail` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1442 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1440 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1879 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1875 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1869 | `nyc npm run _mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1867 | `mocha tests.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1863 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1857 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1856 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1847 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1833 | `mocha test/*.test.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1811 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1806 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1798 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1783 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1779 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1777 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1777 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1768 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1766 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1764 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1735 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1721 | `mocha && npm run lint` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1717 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1708 | `npm run lint && npm run mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1706 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1705 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1704 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1704 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1702 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1698 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1697 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1689 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1687 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1668 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1657 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1652 | `npm run lint && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1644 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1636 | `mocha ./test/basic.js -t 5000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1635 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1617 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1615 | `mocha --compilers js:babel-register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1614 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1612 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1609 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1593 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1592 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1587 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1576 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1540 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1527 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1516 | `mocha --reporter spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1516 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1512 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1505 | `npm run test:lint && npm run test:mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1516 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1512 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1505 | `npm run test:lint && npm run test:mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1504 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1501 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1496 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1487 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1481 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1480 | `mocha -u tdd` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1479 | `standard "./src/*.js" && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1476 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1473 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1437 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1432 | `mocha test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1431 | `nyc npm run mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1430 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1394 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1365 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1358 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1354 | `istanbul cover _mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1351 | `mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1348 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1329 | `npm run build && mocha -r should` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1328 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1319 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1314 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1313 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1280 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1279 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1279 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1277 | `mocha spec/exec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1271 | `mocha --opts test/opts/mocha.opts` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1264 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1263 | `mocha test/unit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1262 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1250 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1250 | `eslint src && mocha && karma start --single-run` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1249 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1246 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1239 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1237 | `mocha test/*.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1235 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1229 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1229 | `standard && istanbul cover _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1226 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1225 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1224 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1304 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1297 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1297 | `mocha --check-leaks --require @babel/register` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1297 | `mocha-phantomjs tests/index.html` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1292 | `nyc mocha --timeout=20000 test.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1291 | `./node_modules/.bin/mocha test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1289 | `istanbul cover _mocha test -- --timeout 20000` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1280 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1279 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1279 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1277 | `mocha spec/exec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1271 | `mocha --opts test/opts/mocha.opts` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1264 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1263 | `mocha test/unit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1262 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1250 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1250 | `eslint src && mocha && karma start --single-run` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1249 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1246 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1239 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1237 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1237 | `mocha test/*.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1235 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1229 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1229 | `standard && istanbul cover _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1226 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1225 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1224 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1223 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1190 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1185 | `mocha test` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1176 | `mocha src/test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1160 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1142 | `TEST=all mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1128 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1115 | `mocha ./test/test*.js --reporter spec` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1110 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1098 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1089 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1082 | `mocha --check-leaks -t 20000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1156 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1153 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1146 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1142 | `TEST=all mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1137 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1128 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1115 | `NODE_ENV=test mocha tests/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1112 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1110 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1109 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1107 | `npm run prepublishOnly && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1105 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1115 | `mocha ./test/test*.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1115 | `NODE_ENV=test mocha tests/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1112 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1110 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1109 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1107 | `npm run prepublishOnly && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1105 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1103 | `mocha --recursive test` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1101 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1098 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1097 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1097 | `mocha $(find test -name '*.test.js')` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1036 | `standard && mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1035 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1029 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1023 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1021 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1008 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1004 | `mocha $(find test -name '*.test.js')` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1003 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1000 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 988 | `mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 986 | `npm run lint && mocha --require @babel/register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1049 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1046 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1046 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1044 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1044 | `webpack && npm run lint && npm run mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1044 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1042 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1037 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1036 | `standard && mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1035 | `mocha test/tests.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1029 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1026 | `mocha --recursive --bail --reporter spec test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1023 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1023 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [electron/asar](https://github.com/electron/asar) | 1012 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1011 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1008 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1008 | `webpack && mocha test/unit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1004 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1000 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 989 | `mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 988 | `mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 986 | `npm run lint && mocha --require @babel/register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 986 | `standard && mocha -b` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 986 | `npm run lint && mocha --require @babel/register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 986 | `standard && mocha -b` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 978 | `mocha && standard` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 972 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 969 | `mocha -R list` | 
| [odota/core](https://github.com/odota/core) | 969 | `NODE_ENV=test mocha --exit` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 959 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 959 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 958 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 958 | `mocha --timeout 20000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 969 | `mocha -R list` | 
| [odota/core](https://github.com/odota/core) | 969 | `NODE_ENV=test mocha --exit` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 966 | `eslint src test && mocha --compilers babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 959 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 959 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 958 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 958 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 954 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 953 | `npm run mocha:istanbul` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 948 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 948 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 948 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 940 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 890 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 870 | `node_modules/.bin/mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 890 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 870 | `node_modules/.bin/mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 869 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 864 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 862 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 861 | `mocha -t 600000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 860 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 860 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 859 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 859 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 858 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 851 | `eslint test && mocha --compilers js:babel/register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 850 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 848 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 839 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 835 | `NODE_ENV=test mocha --exit` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 833 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 831 | `mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 831 | `standard && standard ./bin/* && mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 831 | `mocha spec/*.js` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 829 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 827 | `nyc mocha specs` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 825 | `./node_modules/.bin/mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 823 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 821 | `istanbul cover -- _mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 820 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 819 | `mocha test --compilers js:babel-core/register` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 819 | `mocha test --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 812 | `npm run lint && mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 812 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 806 | `nyc mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 804 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 806 | `nyc mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 804 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 798 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 797 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 796 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 795 | `./node_modules/.bin/mocha --reporter spec` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 794 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 789 | `mocha --async-only` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 785 | `mocha --timeout 30000 --recursive ./tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 785 | `mocha test` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 783 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 782 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [edsu/anon](https://github.com/edsu/anon) | 782 | `mocha --colors --reporter spec test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 782 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 778 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 772 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 681 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 680 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 675 | `./node_modules/.bin/mocha test/**/*` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 672 | `mocha -b -R spec test/*` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 668 | `mocha $(find test -name '*.test.js')` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 667 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 667 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 664 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 664 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 750 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 749 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 748 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 748 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 747 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 742 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 742 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 740 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 739 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 724 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 722 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 722 | `nyc npm run mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 721 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 717 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 716 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 715 | `npm run lint && npm run mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 714 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 712 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 668 | `mocha $(find test -name '*.test.js')` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 667 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 667 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 664 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 664 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 663 | `nyc mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [koajs/static](https://github.com/koajs/static) | 658 | `mocha --harmony --reporter spec --exit` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 656 | `./node_modules/.bin/mocha test/integration` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 656 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 655 | `npm run test-mocha && npm run test-karma` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 654 | `mocha -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 703 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 702 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 701 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 697 | `mocha ./test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 697 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 696 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 694 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 694 | `mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 691 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 691 | `mocha --reporter spec build/test/index.js` | 
| [scality/S3](https://github.com/scality/S3) | 689 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 