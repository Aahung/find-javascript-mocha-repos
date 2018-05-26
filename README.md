# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:50 05/26/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41689 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40588 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38466 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29531 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24027 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23272 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22510 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22212 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18858 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18338 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16254 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15810 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14278 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14110 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13410 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12695 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12443 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12262 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12140 | `mocha` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12135 | `mocha --reporter spec` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12054 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11736 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11094 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10919 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10464 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10329 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9917 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9686 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9682 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9640 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9607 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9145 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8862 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8822 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8748 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8659 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 8608 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8344 | `mocha test/test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8335 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8300 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8288 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8213 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8187 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8123 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8002 | `mocha --compilers js:babel-register test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7946 | `mocha tests/*.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7920 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7732 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7670 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7570 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7520 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7514 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7469 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7324 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7114 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7018 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6971 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6840 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6829 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6817 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6765 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6758 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6664 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6540 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6257 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6113 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6106 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6091 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6026 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6010 | `npm run build-cli && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5830 | `mocha test node-test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5819 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5803 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5793 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5024 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4914 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4911 | `standard && mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4892 | `gulp lint && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4847 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4814 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4716 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4691 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4672 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4643 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4640 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4571 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4552 | `mocha ./test/runner.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5024 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4914 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4911 | `standard && mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4892 | `gulp lint && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4847 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4814 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4716 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4691 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4672 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4643 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4640 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4575 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4571 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4552 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4486 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4460 | `mocha test` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4444 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4414 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4343 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4320 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4317 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4220 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4188 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4186 | `NODE_ENV=test mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4136 | `nyc mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4089 | `nyc mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 4076 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4063 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3968 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3914 | `nyc mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3893 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3891 | `mocha -R spec ./test` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3872 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3848 | `npm run lint ; mocha && mocha test/individual` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3806 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3770 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3763 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3760 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3693 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3661 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3617 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3580 | `npm run build && mocha test/*.test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3570 | `mocha --check-leaks --reporter spec --bail` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3559 | `mocha tests/javascript` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3530 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3497 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3476 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3459 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3428 | `node_modules/.bin/mocha test/lib/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3424 | `nyc mocha "test/**/*.test.js"` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3419 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3412 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3405 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3390 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3378 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3338 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3329 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3328 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3297 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3242 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3161 | `NODE_ENV=test mocha test/**/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3123 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3113 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3112 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3111 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3108 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3067 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3061 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3022 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3007 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3007 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3002 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2984 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2973 | `mocha test/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2961 | `NODE_ENV=test mocha --exit` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2948 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2920 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2911 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2834 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2833 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2831 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2799 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2788 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2775 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2763 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2739 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2727 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2719 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2716 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2685 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2665 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [css/csso](https://github.com/css/csso) | 2664 | `mocha --reporter dot` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2657 | `export TESTING=true; mocha --reporter list` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2657 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2637 | `mocha --require babel-register --recursive spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2587 | `mocha --recursive --watch` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2569 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2553 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2540 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2525 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2521 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2507 | `mocha -R landing test/index` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2490 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2474 | `npm run build && cd test && mocha . --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2458 | `mocha --reporter=spec test/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2437 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2436 | `nyc --reporter=html --reporter=text mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2401 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2394 | `mocha "test/**/*-test.js"` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2385 | `mocha test/src/**/*.unit.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2637 | `mocha --require babel-register --recursive spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2621 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2587 | `mocha --recursive --watch` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2569 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2569 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2553 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2540 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2525 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2521 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2507 | `mocha -R landing test/index` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2394 | `mocha "test/**/*-test.js"` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2385 | `mocha test/src/**/*.unit.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2376 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2371 | `mocha test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2367 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2362 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2352 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2340 | `mocha --no-colors --reporter spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2339 | `mocha test/unit --require mochahook` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2334 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2316 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2288 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2285 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2281 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2334 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2316 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2288 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2285 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2281 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2254 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2240 | `mocha -R spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2236 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2206 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2187 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2157 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2143 | `mocha test && npm run lint` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2139 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2132 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2107 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2104 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2082 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2079 | `eslint . && mocha -t 5000` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2078 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1797 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1796 | `mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1791 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1787 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1780 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1769 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1767 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1763 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1759 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1758 | `mocha -R spec spec spec/reporters` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [pahen/madge](https://github.com/pahen/madge) | 1725 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1720 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1716 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1711 | `mocha && npm run lint` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1702 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1700 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1700 | `npm run lint && npm run mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1696 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1692 | `mocha --reporter spec --grep .` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1691 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1690 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1686 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1685 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1659 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1649 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1645 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1637 | `mocha test/*.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1637 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1633 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1633 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1632 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1628 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1626 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1611 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1609 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1609 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1601 | `mocha spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1601 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1593 | `mocha --compilers js:babel-register` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1589 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1584 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1559 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1550 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1538 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1530 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1523 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1511 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1508 | `mocha --reporter spec` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1492 | `eslint --cache . && tsc && mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1491 | `mocha compiled_tests/` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1482 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1471 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1470 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1470 | `mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1467 | `mocha tests.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1461 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1460 | `nyc mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1455 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1455 | `mocha test/**/*.spec.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1451 | `mocha test/setup.js test/spec/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1448 | `mocha test/tests.js --timeout=10000` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1457 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1455 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1455 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1448 | `mocha test/tests.js --timeout=10000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1442 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1437 | `mocha --check-leaks --reporter spec --bail` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1433 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1430 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1429 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1421 | `mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1420 | `nyc npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1416 | `mocha test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1342 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1322 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1316 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1306 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1304 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1298 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1329 | `mocha test` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1322 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1316 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1306 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1304 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1298 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1292 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1298 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1292 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1284 | `./node_modules/.bin/mocha test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1279 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1279 | `istanbul cover _mocha test -- --timeout 20000` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1276 | `mocha --check-leaks --require @babel/register` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1274 | `mocha spec/exec.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1274 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1271 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1270 | `nyc mocha --timeout=20000 test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1262 | `mocha --opts test/opts/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1257 | `mocha test/unit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1256 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1245 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1245 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1241 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1240 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1239 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1236 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1234 | `eslint src && mocha && karma start --single-run` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1225 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1221 | `standard && istanbul cover _mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1220 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1219 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1218 | `mocha --reporter dot` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1215 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1215 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1213 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1210 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1204 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1201 | `mocha test/**/*Spec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1192 | `mocha tests/test-*` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1192 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1191 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1188 | `node ./node_modules/mocha/bin/mocha tests` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1187 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1185 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1183 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1183 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1174 | `mocha src/test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1173 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1173 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1170 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1166 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1163 | `mocha --reporter spec` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1156 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1156 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1148 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1147 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1142 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1134 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1133 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1130 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1130 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1121 | `mocha` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1106 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1102 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1099 | `npm run prepublishOnly && mocha test/test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1099 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1096 | `NODE_ENV=test mocha tests/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1093 | `mocha $(find test -name '*.test.js')` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1090 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1090 | `mocha --recursive test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1086 | `mocha ./test/test*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1086 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1085 | `mocha test/*` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1085 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1081 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1091 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1090 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1090 | `mocha --recursive test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1086 | `mocha ./test/test*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1086 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1085 | `mocha test/*` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1085 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1081 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1079 | `mocha --check-leaks -t 20000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1079 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1073 | `istanbul cover _mocha test/*.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1071 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1070 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1069 | `npm run lint && npm run mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1067 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1067 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1060 | `TEST=all mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1059 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1046 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1045 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1045 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1041 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1040 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1033 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1030 | `mocha test/tests.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1028 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1021 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1019 | `mocha --recursive --bail --reporter spec test` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1018 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1010 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1007 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1006 | `webpack && mocha test/unit` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1010 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1007 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1006 | `webpack && mocha test/unit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1001 | `mocha $(find test -name '*.test.js')` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 998 | `mocha -t 120000 test/*.test.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 997 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 996 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 991 | `mocha --recursive test/bin` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 988 | `nyc mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 986 | `mocha --recursive test/unit/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 985 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 983 | `standard && mocha -b` | 
| [tomas/needle](https://github.com/tomas/needle) | 981 | `mocha test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 979 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 960 | `eslint src test && mocha --compilers babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 958 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 948 | `mocha --timeout 5000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 947 | `mocha --timeout 20000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 944 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 943 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 940 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 938 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 937 | `npm run mocha:istanbul` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 921 | `mocha "client.test" --compilers js:babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 920 | `npm run convertto:es5 && npm run mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 917 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 914 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 911 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 906 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 906 | `mocha --compilers js:babel-register test/*.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 901 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 898 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 890 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 889 | `npm run lint && mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 886 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) | 880 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js 'test/**/*.@(js|jsx)'` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 901 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 898 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 897 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 890 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 889 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 888 | `mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 886 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) | 880 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js 'test/**/*.@(js|jsx)'` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 878 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 868 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 867 | `node_modules/.bin/mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 867 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 861 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 858 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 857 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 857 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 857 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 856 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 855 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 850 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 850 | `eslint test && mocha --compilers js:babel/register` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 843 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 834 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 831 | `mocha --check-leaks -t 20000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 828 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 827 | `istanbul cover _mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 824 | `mocha spec/*.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 831 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 830 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 828 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 827 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 826 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 824 | `mocha spec/*.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 823 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 823 | `mocha test --compilers js:babel-register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 820 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 818 | `./node_modules/.bin/mocha -R spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 817 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 817 | `istanbul cover -- _mocha --reporter spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 803 | `nyc mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 800 | `mocha --reporter list` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 800 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 800 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 795 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 784 | `mocha --async-only` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 797 | `mocha test --compilers js:babel-core/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 795 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 784 | `mocha --async-only` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 783 | `./node_modules/.bin/mocha --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 782 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 761 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 758 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 758 | `npm run mocha-test test/integration` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 758 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 757 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 757 | `mocha --timeout 30000 --recursive ./tests` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 755 | `nyc --check-coverage mocha test/*.test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 752 | `mocha --harmony --full-trace --check-leaks` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 752 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 761 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 758 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 758 | `npm run mocha-test test/integration` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 758 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 757 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 757 | `mocha --timeout 30000 --recursive ./tests` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 756 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 755 | `nyc --check-coverage mocha test/*.test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 752 | `mocha --harmony --full-trace --check-leaks` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 752 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 751 | `mocha test` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 749 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 748 | `mocha --recursive ./test/*_spec.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 747 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 745 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 744 | `mocha --recursive -s 15 test/` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 744 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 744 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 741 | `mocha test/index.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 740 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 739 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 737 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 731 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 731 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 730 | `mocha test` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 729 | `mocha test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 728 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 724 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 724 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 724 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 720 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 720 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 716 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 712 | `npm run lint && npm run mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 711 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 710 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 708 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 707 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 704 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 704 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 701 | `mocha -r should --reporter spec test/*.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 698 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 638 | `mocha --compilers js:babel-register` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 638 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [shime/livedown](https://github.com/shime/livedown) | 633 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 628 | `mocha --reporter spec` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 626 | `mocha --reporter spec` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 626 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 626 | `mocha` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 625 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 623 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 622 | `jenkins-mocha ./tests/*.js` | 