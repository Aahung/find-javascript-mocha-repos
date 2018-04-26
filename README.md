# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:00 04/26/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41008 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40310 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 40247 | `npm run mocha` | 
| [expressjs/express](https://github.com/expressjs/express) | 37897 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29304 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23853 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22974 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21797 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21773 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18531 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18112 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16038 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15528 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14011 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13938 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13184 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12530 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12325 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12107 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12104 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11934 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11835 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11390 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10926 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10649 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10212 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10095 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9712 | `mocha test/index.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9590 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9576 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9493 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9446 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9075 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8870 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8740 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8649 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8610 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8363 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8264 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8259 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8164 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8161 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8103 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8070 | `./node_modules/.bin/mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 7952 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7935 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7876 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7714 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7679 | `npm run eslint && npm run mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7492 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7442 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7435 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7373 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7334 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7286 | `npm run build && istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7246 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6887 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6861 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6828 | `npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6773 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6704 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6690 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6690 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6686 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6676 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6544 | `mocha --compilers js:babel-core/register` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5229 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5150 | `mocha; jshint *.js lib` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5052 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4858 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4851 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4793 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4778 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4769 | `standard && mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4690 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4673 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4653 | `mocha --reporter spec -t 8000` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5569 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5540 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5516 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5401 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5387 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5237 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5229 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5150 | `mocha; jshint *.js lib` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5052 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4940 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4858 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4851 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4793 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4778 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4769 | `standard && mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4690 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4673 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4653 | `mocha --reporter spec -t 8000` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4595 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4592 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4549 | `mocha ./test/runner.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4527 | `mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4525 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4436 | `./node_modules/.bin/mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4424 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4406 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4370 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4301 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4283 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4107 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4072 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4065 | `nyc mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3978 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3973 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3951 | `mocha --require test/babel-hook test/*.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3931 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3925 | `mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3897 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3888 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3863 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3848 | `mocha --require should --reporter spec` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3847 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3838 | `mocha -R spec ./test` | 
| [erming/shout](https://github.com/erming/shout) | 3809 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3762 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3711 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3670 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3666 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3657 | `npm run jshint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3650 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3633 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3608 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3557 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3553 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3549 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3483 | `mocha --reporter spec --timeout 3000` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3480 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3465 | `mocha --check-leaks --reporter spec --bail` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3450 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3445 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3422 | `node_modules/.bin/mocha test/lib/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3421 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3413 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3334 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3326 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3321 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3311 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3273 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3269 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3252 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3177 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3168 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3103 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3102 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3100 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3098 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3055 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3043 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3042 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3039 | `NODE_ENV=test mocha test/**/*.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2988 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 2986 | `nyc mocha && tsc` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2961 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2942 | `mocha test/*.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2933 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2918 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2917 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2915 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2910 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2854 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2850 | `mocha test/index.js && npm run demo` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2836 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2830 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2818 | `mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2814 | `NODE_ENV=test mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2814 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2806 | `mocha -R spec --recursive src/test` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2792 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2789 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2788 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2786 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2774 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2774 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2770 | `mocha --require should --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2755 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2734 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2733 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2712 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2703 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2674 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2661 | `xo && mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2648 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2641 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2641 | `npm run mocha && npm run lint` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2637 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2632 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2631 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [css/csso](https://github.com/css/csso) | 2629 | `mocha --reporter dot` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2628 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2610 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2609 | `mocha --timeout 100000` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2606 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2605 | `mocha --require babel-register --recursive spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2596 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2560 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2533 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2525 | `export TESTING=true; mocha --reporter list` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2519 | `export TESTING=true; mocha --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2519 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2505 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2487 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2469 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2450 | `mocha --reporter=spec test/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2450 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2440 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2417 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2397 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2372 | `nyc --reporter=html --reporter=text mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2366 | `mocha -R landing test/index` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2363 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2362 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2360 | `mocha --require should --reporter spec` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2358 | `mocha test` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2342 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2338 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2337 | `grunt jshint && mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2331 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2324 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2289 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2284 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2280 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2275 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2266 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2260 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2256 | `mocha test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2244 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2238 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2226 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2222 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2215 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2172 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2169 | `mocha --compilers js:babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2091 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2091 | `cross-env BABEL_ENV=test mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2089 | `mocha && eslint .` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2084 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [noble/noble](https://github.com/noble/noble) | 2082 | `mocha -R spec test/*.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2080 | `mocha test && npm run lint` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2073 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2066 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2004 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1981 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1970 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1958 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2004 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1981 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1970 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1958 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1949 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1943 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1924 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1918 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1915 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1914 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1909 | `mocha --bail --reporter spec --check-leaks test/` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1893 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1892 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1885 | `eslint . && mocha -t 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1873 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1871 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1863 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1853 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1845 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1845 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1841 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [then/promise](https://github.com/then/promise) | 1828 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [then/promise](https://github.com/then/promise) | 1828 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1815 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [share/sharedb](https://github.com/share/sharedb) | 1813 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1807 | `mocha && eslint *.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1804 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [kach/nearley](https://github.com/kach/nearley) | 1801 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1798 | `npm run lint && mocha -R dot && npm run cover` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1792 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1777 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1773 | `nyc npm run _mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1772 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1769 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1761 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1757 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1753 | `npm run lint && mocha --reporter spec test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1748 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1741 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1736 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1736 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1734 | `npm run mocha && npm run karma` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1727 | `mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1713 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1699 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 1685 | `npm run lint && npm run mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1685 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1681 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1681 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1677 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1675 | `mocha && npm run lint` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1664 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1660 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1652 | `mocha tests --compilers js:babel-core/register` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1646 | `standard "src/*.js" && npm run build && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1638 | `mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1637 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1626 | `mocha test -u bdd -R spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1624 | `mocha --expose-gc --slow 300` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1618 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1618 | `mocha tests/test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1616 | `mocha test/**/*.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1616 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1611 | `mocha ./test/basic.js -t 5000` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1605 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1603 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1601 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1594 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1591 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1584 | `mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1572 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1570 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1562 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1548 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1547 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1537 | `mocha --compilers js:babel-register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1533 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1530 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1517 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1507 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1507 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1492 | `npm run test:lint && npm run test:mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1491 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1490 | `mocha --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1476 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1464 | `node_modules/.bin/mocha --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1463 | `eslint --cache . && tsc && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1456 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1448 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1445 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1436 | `nyc mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1435 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1435 | `mocha test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1434 | `mocha tests.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1434 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1426 | `standard "./src/*.js" && mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1426 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1424 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1423 | `mocha compiled_tests/` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1413 | `mocha test.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1406 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1398 | `mocha --check-leaks --reporter spec --bail` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1396 | `mocha --recursive` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1395 | `mocha test/setup.js test/spec/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1383 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1376 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1375 | `nyc npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1372 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1369 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1361 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1340 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1340 | `istanbul cover _mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1330 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1327 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1327 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1312 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1297 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1293 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1290 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1284 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1284 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1276 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1271 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1269 | `mocha spec/exec.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1258 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1258 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1248 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1247 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1247 | `mocha --recursive` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1245 | `mocha test` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1234 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1233 | `mocha test/*.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1213 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1211 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1211 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1211 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1206 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1204 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1201 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1198 | `mocha test/**/*Spec.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1189 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1189 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1187 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1182 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1181 | `node ./node_modules/mocha/bin/mocha tests` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1180 | `nyc mocha --timeout=20000 test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1180 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1177 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1171 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1189 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1188 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1187 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1182 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1181 | `node ./node_modules/mocha/bin/mocha tests` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1180 | `mocha --reporter dot` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1180 | `nyc mocha --timeout=20000 test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1180 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1177 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1171 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1168 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1164 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1152 | `node_modules/.bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1150 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1124 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1123 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1120 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1107 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1104 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1098 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1097 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1093 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1086 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1107 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1104 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1098 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1097 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1093 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1086 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1081 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1080 | `mocha $(find test -name '*.test.js')` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1077 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1071 | `mocha --compilers js:babel-register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1070 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1061 | `npm run prepublishOnly && mocha test/test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1059 | `mocha -R spec ./test/unit/**` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1059 | `NODE_PATH=. mocha **/*.spec.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1057 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1056 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1052 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1050 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1049 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1042 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1034 | `mocha --recursive test` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1028 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1025 | `mocha test/tests.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1024 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1022 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1022 | `npm run lint && npm run mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1019 | `mocha --compilers js:babel-core/register` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1018 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1018 | `mocha tests/*.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1017 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1017 | `mocha ./test/test*.js --reporter spec` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1016 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1012 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1008 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1007 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1004 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1002 | `mocha --recursive --bail --reporter spec test` | 
| [router5/router5](https://github.com/router5/router5) | 1001 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1000 | `mocha --colors ./test/*.spec.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 998 | `standard && mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 995 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 992 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 988 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 985 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 981 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [electron/asar](https://github.com/electron/asar) | 981 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 980 | `webpack && mocha test/unit` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 979 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 977 | `mocha` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 977 | `mocha -t 120000 test/*.test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 971 | `TEST=all mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 970 | `mocha test` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 968 | `mocha --recursive test/unit/` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 967 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 966 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 965 | `mocha --async-only` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 964 | `mocha -R list` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 961 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 959 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 957 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 954 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 953 | `mocha && standard` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 952 | `mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 948 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 947 | `eslint src test && mocha --compilers babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 945 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 939 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 936 | `npm run lint && mocha --require @babel/register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 926 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 924 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 921 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 917 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 917 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 909 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 908 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 906 | `mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 901 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 900 | `mocha ./test -R spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 897 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 895 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 894 | `mocha --compilers js:babel-register test/*.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 894 | `npm run convertto:es5 && npm run mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 890 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 888 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 888 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 886 | `npm-run-all test:jest test:mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 883 | `mocha --timeout 20000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 881 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 881 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 880 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 876 | `npm run lint && mocha -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 860 | `mocha tests` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 849 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 848 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 848 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 845 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 843 | `eslint test && mocha --compilers js:babel/register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 841 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 834 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 833 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 843 | `eslint test && mocha --compilers js:babel/register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 841 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 835 | `mocha -t 600000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 834 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 833 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 826 | `mocha --check-leaks -t 20000` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 823 | `istanbul cover _mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 823 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 822 | `mocha --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 821 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 821 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 819 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 819 | `standard && standard ./bin/* && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 818 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 817 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 812 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 811 | `nyc mocha specs` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 811 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 809 | `mocha test --compilers js:babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 805 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 805 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 803 | `istanbul cover -- _mocha --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 803 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 801 | `./node_modules/.bin/mocha -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 799 | `mocha --require babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 796 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 791 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 791 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 786 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 785 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 783 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 778 | `mocha --async-only` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 774 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 772 | `npm run lint && mocha` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 772 | `nyc mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 769 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 764 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 760 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 756 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 755 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 752 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 752 | `mocha -R spec src/**/*_test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 752 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 750 | `mocha test --compilers js:babel-core/register` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 746 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 744 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 744 | `mocha test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 743 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 737 | `mocha --recursive -s 15 test/` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 737 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [developit/decko](https://github.com/developit/decko) | 731 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 730 | `nyc --check-coverage mocha test/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 730 | `./node_modules/.bin/mocha --reporter spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 729 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 729 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 728 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 728 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 728 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 728 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 727 | `mocha --harmony --full-trace --check-leaks` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 727 | `mocha test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 725 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 724 | `mocha test` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 722 | `mocha test` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 721 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 720 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 719 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 