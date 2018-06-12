# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:01 06/12/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42073 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40713 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38729 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29658 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24112 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23457 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 23080 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22423 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19064 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18472 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16341 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15958 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14453 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14157 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13516 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12768 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12514 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12498 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12360 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12159 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12114 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11938 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10031 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9746 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9733 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9706 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9507 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9236 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9172 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9013 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8852 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8807 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8528 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8396 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8306 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8246 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8226 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8030 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7956 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9236 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9172 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9013 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8852 | `grunt mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8812 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8807 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8528 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8396 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8368 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8306 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8246 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8226 | `grunt clean:test && mocha --exit` | 
| [amark/gun](https://github.com/amark/gun) | 8191 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8076 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8030 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7956 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7803 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7752 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7620 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7615 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7526 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7517 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7346 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7098 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7095 | `mocha --opts mocha.opts` | 
| [aui/art-template](https://github.com/aui/art-template) | 6908 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6908 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6903 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6837 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6790 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6732 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6321 | `npm run lint -s && npm run mocha -s` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6220 | `mocha test node-test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6189 | `npm run build-cli && mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6184 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6142 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6116 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5909 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5856 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5852 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5752 | `mocha; jshint *.js lib` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5736 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5537 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5280 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5161 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5147 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4990 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4988 | `standard && mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4899 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4823 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4718 | `mocha test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4701 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4699 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4673 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4662 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4659 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5147 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4990 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4988 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4941 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4899 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4823 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4718 | `mocha test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4701 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4699 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4673 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4662 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4659 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4609 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4592 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4556 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4520 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4504 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4419 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4369 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4345 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4248 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4228 | `mocha --recursive && make test` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4219 | `mocha -R spec ./test --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4200 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4135 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4106 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3974 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3969 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3961 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3953 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3907 | `mocha --require should --reporter spec` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3888 | `npm run lint && npm run mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3883 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3879 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3875 | `npm run lint ; mocha && mocha test/individual` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3818 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3809 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3775 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3698 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3660 | `npm run jshint && npm run mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3630 | `mocha --check-leaks --reporter spec --bail` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3620 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3596 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3561 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3512 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3502 | `mocha --reporter spec --timeout 3000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3512 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3502 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3485 | `node_modules/.bin/mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3469 | `nyc mocha "test/**/*.test.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3466 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3454 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3451 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3432 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3426 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3421 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3414 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3386 | `node_modules/.bin/mocha test/tests.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3380 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3368 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3342 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3295 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3079 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3058 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3054 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3034 | `NODE_ENV=test mocha --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3007 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3000 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2966 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2950 | `mocha test/index.js && npm run demo` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2895 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2877 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2850 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2845 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2841 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2838 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2841 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2838 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2814 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2794 | `istanbul cover _mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2783 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2777 | `mocha --require should --reporter spec` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2772 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2771 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2762 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2761 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2742 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2742 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2735 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2706 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2705 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2683 | `xo && mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2678 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2673 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2671 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2663 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2622 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2606 | `node_modules/.bin/mocha --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2590 | `mocha --recursive --watch` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2574 | `mocha -R landing test/index` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2563 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2559 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2547 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2512 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2502 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2496 | `npm run build && cd test && mocha . --reporter dot` | 
| [json5/json5](https://github.com/json5/json5) | 2465 | `nyc --reporter=html --reporter=text mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2678 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2673 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2671 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2663 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2627 | `mocha --timeout 100000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2622 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2606 | `node_modules/.bin/mocha --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2590 | `mocha --recursive --watch` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2574 | `mocha -R landing test/index` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2563 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2559 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2547 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2540 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2512 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2502 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2496 | `npm run build && cd test && mocha . --reporter dot` | 
| [json5/json5](https://github.com/json5/json5) | 2465 | `nyc --reporter=html --reporter=text mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2459 | `mocha --reporter=spec test/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2454 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2425 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2422 | `mocha test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2419 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2414 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2411 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2392 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2374 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2364 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2358 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2358 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2350 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2343 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2311 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2297 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2289 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2259 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2257 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2249 | `nyc --reporter=html --reporter=text mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2248 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2233 | `eslint . && mocha -t 5000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2164 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2128 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2110 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2090 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2086 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2074 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2044 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [slate/slate](https://github.com/slate/slate) | 2009 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1992 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1984 | `mocha test/runner.js --reporter spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1977 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1974 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1951 | `mocha --require=test/test_helper.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1928 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1923 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1921 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1921 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1914 | `mocha --compilers js:babel-core/register __tests__` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1912 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1909 | `mocha --reporter spec --timeout 5000` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1905 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1889 | `nyc npm run _mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1886 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1884 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1873 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1866 | `./node_modules/.bin/mocha && npm run jshint` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1865 | `mocha tests.js` | 
| [then/promise](https://github.com/then/promise) | 1860 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1856 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1840 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1830 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1828 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1815 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1810 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1800 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1788 | `mocha --reporter spec && npm run test-typescript` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1786 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1781 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1781 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1771 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1770 | `mocha -R spec spec spec/reporters` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1769 | `npm run lint && mocha --reporter spec test/*.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1678 | `mocha test/**/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1667 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1665 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1655 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1642 | `mocha ./test/basic.js -t 5000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1640 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1636 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1627 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1620 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1611 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1611 | `mocha && size-limit` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1608 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1589 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1589 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1555 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1544 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1529 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1517 | `mocha compiled_tests/` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1516 | `mocha --reporter spec` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1513 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1620 | `mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1611 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1611 | `mocha && size-limit` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1608 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1607 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1605 | `mocha test/* --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1589 | `mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1331 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1305 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1300 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1292 | `./node_modules/.bin/mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1286 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1283 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1283 | `mocha spec/exec.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1276 | `mocha test/unit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1259 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1442 | `nyc npm run mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1440 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1435 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1432 | `mocha --recursive` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1386 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1381 | `mocha test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1372 | `mocha --timeout 10000 ./tests/lib.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1371 | `./node_modules/mocha/bin/mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1440 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1435 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1432 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1396 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1386 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1381 | `mocha test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1327 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1322 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1317 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1306 | `mocha --check-leaks --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1305 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1295 | `istanbul cover _mocha test -- --timeout 20000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1287 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1286 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1283 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1283 | `mocha spec/exec.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1281 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1276 | `mocha --opts test/opts/mocha.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1331 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1331 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1327 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1322 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1320 | `nyc mocha --timeout=20000 test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1317 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1306 | `mocha --check-leaks --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1305 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1300 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1295 | `istanbul cover _mocha test -- --timeout 20000` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1287 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1281 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1276 | `mocha --opts test/opts/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1255 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1248 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1244 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1238 | `mocha test/*.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1236 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1235 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1224 | `mocha tests/test-*` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1223 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1248 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1244 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1242 | `mocha --timeout 60000 test/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1238 | `mocha test/*.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1236 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1235 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1234 | `standard && istanbul cover _mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1233 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1228 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1226 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1225 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1224 | `mocha tests/test-*` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1223 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1214 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1213 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1202 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1202 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1194 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1191 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1189 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1188 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1187 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1187 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1183 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1182 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1175 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [normalize/mz](https://github.com/normalize/mz) | 1172 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1171 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1167 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1166 | `TEST=all mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1164 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1162 | `mocha --check-leaks --reporter spec --bail test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1161 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1146 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1144 | `mocha -R spec ./test/unit/**` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1143 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1138 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1137 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1135 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1133 | `NODE_ENV=test mocha tests/*.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1131 | `mocha ./test/test*.js --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1130 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1123 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1122 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1120 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1117 | `npm run prepublishOnly && mocha test/test.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1117 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1116 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1115 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1113 | `mocha --recursive test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1108 | `mocha --recursive test/bin` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1104 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1102 | `npm run lint && npm run mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1099 | `mocha $(find test -name '*.test.js')` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1098 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1097 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1097 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1093 | `xo && mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 989 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 989 | `standard && mocha -b` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 978 | `mocha --async-only` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 972 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 967 | `mocha --timeout 20000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 955 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 953 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [poooi/poi](https://github.com/poooi/poi) | 1055 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1054 | `istanbul test _mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1053 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1051 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1051 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1049 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1049 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1049 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1042 | `standard && mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1042 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1039 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1036 | `mocha test/tests.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1031 | `mocha --recursive --bail --reporter spec test` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1026 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 955 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 953 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 934 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 930 | `mocha "client.test" --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 929 | `npm-run-all test:jest test:server:mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 978 | `mocha --async-only` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 976 | `npm run mocha:istanbul` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 975 | `eslint src test && mocha --compilers babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 974 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 972 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 967 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 963 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 961 | `mocha --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 955 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 934 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 930 | `mocha "client.test" --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 929 | `npm-run-all test:jest test:server:mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 920 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 913 | `mocha --compilers js:babel-register test/*.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 912 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 910 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 907 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 903 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 901 | `mocha -R spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 883 | `mocha tests` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 871 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 870 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 865 | `mocha -t 600000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 865 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 861 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 861 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 855 | `mocha spec/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 853 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 852 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 840 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 840 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 839 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 839 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 838 | `mocha -t 5000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 836 | `mocha test --compilers js:babel-core/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 840 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 840 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 839 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 839 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 838 | `mocha -t 5000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 836 | `mocha test --compilers js:babel-core/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 833 | `nyc mocha specs` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 832 | `mocha test --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 831 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 831 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 829 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 828 | `./node_modules/.bin/mocha -R spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 828 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 826 | `istanbul cover -- _mocha --reporter spec` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 779 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 776 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 768 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 767 | `nyc npm run mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 767 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 767 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 761 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 758 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 754 | `npm run build && istanbul test _mocha test/test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 776 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 775 | `nyc --check-coverage mocha test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 769 | `mocha test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 768 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 768 | `mocha --recursive ./test/*_spec.js` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 767 | `nyc npm run mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 767 | `npm run mocha-test test/integration` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 764 | `mocha --harmony --full-trace --check-leaks` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 761 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 761 | `mocha test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 758 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 776 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 775 | `nyc --check-coverage mocha test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 769 | `mocha test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 768 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 768 | `mocha --recursive ./test/*_spec.js` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 767 | `nyc npm run mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 767 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 767 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 764 | `mocha --harmony --full-trace --check-leaks` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 761 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 761 | `mocha test` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 761 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 761 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 761 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 755 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 754 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 752 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 751 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 749 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 747 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 747 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 746 | `mocha --recursive -s 15 test/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 745 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 744 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 737 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 733 | `mocha test` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 733 | `mocha test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 733 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 732 | `mocha --reporter spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 731 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 731 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 681 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 676 | `./node_modules/.bin/mocha test/**/*` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 672 | `mocha -b -R spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 671 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 669 | `mocha $(find test -name '*.test.js')` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 668 | `mocha` | 