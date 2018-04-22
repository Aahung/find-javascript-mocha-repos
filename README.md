# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:45 04/22/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40885 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40277 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 40120 | `npm run mocha` | 
| [expressjs/express](https://github.com/expressjs/express) | 37804 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29260 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23825 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22930 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21730 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21610 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18485 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18081 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16001 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15490 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13998 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13878 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13154 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12509 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12304 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12100 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12072 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11912 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11792 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11330 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10896 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10606 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10182 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10056 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9678 | `mocha test/index.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9571 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9566 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9464 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9426 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9063 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8817 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8723 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8631 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8574 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8329 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8261 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8251 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8161 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8146 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8067 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8057 | `./node_modules/.bin/mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 7929 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7924 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7864 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7679 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7671 | `npm run eslint && npm run mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7274 | `npm run build && istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7215 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6841 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6834 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6775 | `npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6734 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6679 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6679 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6675 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6666 | `mocha $HARMONY_OPTS` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6665 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6525 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6321 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6169 | `npm run lint -s && npm run mocha -s` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6321 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6169 | `npm run lint -s && npm run mocha -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6018 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6017 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6014 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5951 | `npm run jshint && mocha test/` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5737 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5688 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5628 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5614 | `mocha test/test.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5602 | `npm run build-cli && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5546 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5534 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5500 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5363 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5223 | `mocha --timeout 10000 && npm run lint` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5214 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5073 | `mocha; jshint *.js lib` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5027 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4885 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4857 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4841 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4811 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4776 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4755 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4752 | `standard && mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4689 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4664 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4653 | `mocha --reporter spec -t 8000` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4589 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4586 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4547 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4516 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4509 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4431 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4406 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4405 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4358 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4299 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4279 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4098 | `mocha --recursive && make test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4059 | `nyc mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4052 | `NODE_ENV=test mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3961 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3960 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3943 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3926 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3886 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3867 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3865 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3844 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3820 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3814 | `nyc mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3813 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3753 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3703 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3666 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3656 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3655 | `npm run jshint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3624 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3610 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3604 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3556 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3553 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3543 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3485 | `mocha --reporter spec --timeout 3000` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3473 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3447 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3446 | `mocha --check-leaks --reporter spec --bail` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3442 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3422 | `node_modules/.bin/mocha test/lib/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3415 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3412 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3323 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3314 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3312 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3297 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3250 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3218 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3157 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3152 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3103 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3103 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3098 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3096 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3103 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3103 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3098 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3096 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3055 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3037 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3014 | `NODE_ENV=test mocha test/**/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3012 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2988 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 2969 | `nyc mocha && tsc` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2958 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2950 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2937 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2911 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2901 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2897 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2893 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2879 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2840 | `mocha test/index.js && npm run demo` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2824 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2822 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2812 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2812 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2805 | `mocha -R spec --recursive src/test` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2789 | `NODE_ENV=test mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2786 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2779 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2776 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2773 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2769 | `mocha --require should --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2768 | `istanbul cover _mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2763 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2743 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2733 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2732 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2727 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2705 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2691 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2688 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2666 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2658 | `xo && mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2639 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2639 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2632 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2627 | `mocha --reporter dot` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2622 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2621 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2616 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2611 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2606 | `mocha --timeout 100000` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2601 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2599 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2596 | `mocha-phantomjs ./test/index.html` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2596 | `mocha --require babel-register --recursive spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2512 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2491 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2479 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2457 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2440 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2435 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2422 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2410 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2392 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2364 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2363 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2360 | `mocha test/src/**/*.unit.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2422 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2410 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2392 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2364 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2363 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2360 | `mocha test/src/**/*.unit.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2354 | `mocha --require should --reporter spec` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2351 | `mocha test` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2338 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2337 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2336 | `grunt jshint && mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2333 | `mocha -R landing test/index` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2321 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2308 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2283 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2282 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2280 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2088 | `cross-env BABEL_ENV=test mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2086 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2083 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2075 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2072 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2071 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2063 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2063 | `mocha test && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2002 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2088 | `cross-env BABEL_ENV=test mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2086 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2083 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2075 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2072 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2071 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2063 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2063 | `mocha test && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2002 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1975 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1964 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1952 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1945 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1942 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1916 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1913 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1912 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1911 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1908 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1904 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1887 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1883 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1874 | `mocha --reporter spec --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1870 | `mocha --require ./test/common --growl test/expect.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1870 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1860 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1843 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1840 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1831 | `eslint . && mocha -t 5000` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1830 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1829 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [then/promise](https://github.com/then/promise) | 1823 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1808 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1804 | `mocha && eslint *.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1802 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [share/sharedb](https://github.com/share/sharedb) | 1797 | `./node_modules/.bin/mocha && npm run jshint` | 
| [kach/nearley](https://github.com/kach/nearley) | 1797 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1790 | `npm run lint && mocha -R dot && npm run cover` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1783 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1772 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1769 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1767 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1762 | `nyc npm run _mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1756 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1755 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1751 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1744 | `mocha --reporter spec && npm run test-typescript` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1735 | `mocha -R spec spec spec/reporters` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1734 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1733 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1732 | `npm run mocha && npm run karma` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1715 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1710 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1697 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1683 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1680 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1679 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1677 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1675 | `npm run lint && npm run mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1670 | `mocha && npm run lint` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1664 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1658 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1653 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1649 | `mocha tests --compilers js:babel-core/register` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1635 | `standard "src/*.js" && npm run build && mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1625 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1623 | `mocha --expose-gc --slow 300` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1622 | `mocha test -u bdd -R spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1619 | `mocha --reporter spec test/*.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1573 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1559 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1543 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1532 | `mocha --compilers js:babel-register` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1530 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1517 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1517 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [teambit/bit](https://github.com/teambit/bit) | 1509 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1506 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1505 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1543 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1532 | `mocha --compilers js:babel-register` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1530 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1517 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1517 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [teambit/bit](https://github.com/teambit/bit) | 1509 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1506 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1505 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1492 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1486 | `mocha --reporter spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1482 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1469 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1464 | `node_modules/.bin/mocha --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1455 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1453 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1453 | `eslint --cache . && tsc && mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1446 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1446 | `mocha test/**/*.spec.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1439 | `mocha --check-leaks -R dot` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1433 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1432 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1427 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1426 | `mocha test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1423 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1421 | `standard "./src/*.js" && mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1420 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1418 | `mocha compiled_tests/` | 
| [zeit/ms](https://github.com/zeit/ms) | 1414 | `mocha tests.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1413 | `mocha test.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1403 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1395 | `mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1394 | `mocha --check-leaks --reporter spec --bail` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1389 | `mocha test/setup.js test/spec/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1383 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1374 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1372 | `nyc npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1372 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1364 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1338 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1336 | `cross-env NODE_ENV=test nyc mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1327 | `mocha --timeout 10000 ./tests/lib.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1325 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1324 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1310 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1296 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1286 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1286 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1283 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1280 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1274 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1271 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1267 | `mocha spec/exec.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1257 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1256 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1246 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1245 | `mocha --check-leaks --require @babel/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1242 | `mocha --recursive` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1235 | `mocha test` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1233 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1233 | `mocha test/*.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1232 | `mocha --opts test/opts/mocha.opts` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1224 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1222 | `mocha tests` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1212 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1209 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1208 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1207 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1204 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1203 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1201 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1200 | `mocha test/unit` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1197 | `mocha test/**/*Spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1189 | `standard && istanbul cover _mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1189 | `eslint src && mocha && karma start --single-run` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1188 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1187 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1186 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1185 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1183 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1181 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1181 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1179 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1179 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1177 | `mocha test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1176 | `mocha --reporter dot` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1169 | `nyc mocha --timeout=20000 test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1169 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1167 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1152 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1149 | `node_modules/.bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1147 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1143 | `mocha src/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1142 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1141 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1138 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1137 | `npm run lint && npm run mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1134 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1130 | `mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1127 | `mocha tests/test-*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1123 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1122 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1121 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1105 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1105 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1104 | `mocha --check-leaks --reporter spec --bail test/` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1079 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1079 | `xo && mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1071 | `mocha --compilers js:babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1069 | `mocha --check-leaks -t 20000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1069 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1065 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1058 | `npm run prepublishOnly && mocha test/test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1055 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1053 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1049 | `istanbul cover _mocha test/*.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1048 | `mocha -R spec ./test/unit/**` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1039 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1038 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1028 | `mocha --recursive test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1025 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1023 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1021 | `mocha test/tests.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1015 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1014 | `npm run lint && npm run mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1013 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1012 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1012 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1012 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1011 | `mocha --compilers js:babel-core/register` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1008 | `mocha tests/*.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1002 | `mocha ./test/test*.js --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1001 | `mocha --recursive --bail --reporter spec test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1028 | `mocha --recursive test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1025 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1023 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1021 | `mocha test/tests.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1015 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1014 | `npm run lint && npm run mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1013 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1012 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1012 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1012 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1011 | `mocha --compilers js:babel-core/register` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1008 | `mocha tests/*.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1002 | `mocha ./test/test*.js --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1001 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1001 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 999 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 998 | `standard && mocha` | 
| [router5/router5](https://github.com/router5/router5) | 998 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 985 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 983 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 980 | `webpack && npm run lint && npm run mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 979 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 978 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 976 | `webpack && mocha test/unit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron/asar](https://github.com/electron/asar) | 975 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 972 | `mocha` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 972 | `mocha -t 120000 test/*.test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 972 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 964 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 964 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 963 | `mocha test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 962 | `mocha -R list` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 959 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 956 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 956 | `standard && mocha -b` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 955 | `TEST=all mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 954 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 952 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 950 | `mocha --reporter spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 949 | `mocha && standard` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 944 | `eslint src test && mocha --compilers babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 943 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 937 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 936 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 933 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 925 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 923 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 921 | `npm run lint && mocha --require @babel/register` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 918 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 914 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 908 | `mocha "client.test" --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 906 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 906 | `mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 895 | `mocha ./test -R spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 894 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 889 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 889 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 886 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 883 | `npm-run-all test:jest test:mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 880 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 888 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 887 | `npm run convertto:es5 && npm run mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 886 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 883 | `npm-run-all test:jest test:mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 880 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 879 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 874 | `npm run lint && mocha -R spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 874 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 870 | `mocha --timeout 20000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 863 | `mocha -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 861 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 860 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 859 | `mocha tests` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 856 | `node_modules/.bin/mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 854 | `npm run mocha:istanbul` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 852 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 848 | `mocha --timeout 200000` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 847 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 846 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 845 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 843 | `eslint test && mocha --compilers js:babel/register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 835 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 834 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 831 | `mocha -t 600000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 825 | `mocha --check-leaks -t 20000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 822 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 822 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 821 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 820 | `mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 819 | `standard && standard ./bin/* && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 818 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 816 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 816 | `mocha -t 5000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 815 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 818 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 816 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 816 | `mocha -t 5000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 815 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 812 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 811 | `nyc mocha specs` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 810 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 808 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 807 | `mocha test --compilers js:babel-register` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 802 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 802 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 800 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 799 | `./node_modules/.bin/mocha -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 799 | `mocha --require babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 796 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 794 | `mocha spec/*.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 789 | `cake build && mocha ./test/mocha/*.coffee` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 789 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 789 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 786 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 785 | `mocha --reporter list` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 779 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 775 | `mocha --async-only` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 771 | `xo && mocha -R spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 769 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 769 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 769 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 768 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 768 | `nyc mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 745 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 743 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 741 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 740 | `mocha test` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 738 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 735 | `mocha test --compilers js:babel-core/register` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 734 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 734 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 745 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 743 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 741 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 740 | `mocha test` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 738 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 737 | `mocha --recursive -s 15 test/` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 735 | `mocha test --compilers js:babel-core/register` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 734 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 734 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 707 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 704 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 703 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 702 | `mocha --no-timeouts` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 699 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 694 | `mocha test/index.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 693 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 693 | `mocha ./test/index.js` | 