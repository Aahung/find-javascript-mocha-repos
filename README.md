# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:14 04/10/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40571 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40180 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 39653 | `npm run mocha` | 
| [expressjs/express](https://github.com/expressjs/express) | 37593 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29164 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23732 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22787 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21513 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21222 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18325 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17954 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15916 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15358 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13963 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13723 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13057 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12444 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12259 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12082 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11993 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11861 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11625 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11154 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10834 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10499 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10082 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9963 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9597 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9521 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9508 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9381 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9367 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9018 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8718 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8694 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8568 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8442 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8247 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8224 | `mocha --check-leaks -R dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 8209 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8147 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8095 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8014 | `./node_modules/.bin/mocha test/src` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7964 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7874 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7873 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7840 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7634 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7587 | `mocha tests/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7479 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7312 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7277 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7262 | `npm run build && istanbul cover _mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7196 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7069 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6771 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6740 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6664 | `npm run mocha` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6647 | `xo && mocha test/*.js --timeout 100000` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6641 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6640 | `mocha $HARMONY_OPTS` | 
| [aui/art-template](https://github.com/aui/art-template) | 6634 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6596 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6591 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6478 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6215 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6059 | `npm run lint -s && npm run mocha -s` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6012 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5989 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5980 | `npm run test:mocha:src` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5930 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5890 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5717 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5649 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5600 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5542 | `mocha test/test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5511 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5470 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5450 | `npm run build-cli && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5449 | `mocha --exit --require babel-core/register` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5315 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5207 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5160 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5148 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4964 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4886 | `mocha; jshint *.js lib` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4820 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4817 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4768 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4768 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4759 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4687 | `standard && mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4673 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4655 | `mocha -R spec 'tests/app'` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4652 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4643 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4569 | `gulp build; mocha;` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4564 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4543 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4488 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4477 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4415 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4399 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4354 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4312 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4311 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4269 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4265 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4064 | `mocha --recursive && make test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4048 | `nyc mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3988 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3933 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3927 | `npm run lint && npm run mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3910 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3906 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3892 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3859 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3828 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3814 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3794 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3782 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3778 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3762 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3725 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3671 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3654 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3650 | `npm run jshint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3620 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3586 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3556 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3554 | `npm run lint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3551 | `mocha tests/javascript` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3536 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3523 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3478 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3442 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3432 | `node_modules/.bin/mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3426 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3418 | `mocha --check-leaks --reporter spec --bail` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3417 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3411 | `mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3400 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3295 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3279 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3277 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3251 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3238 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3208 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3150 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3117 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3102 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3093 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3092 | `node_modules/.bin/mocha test/tests.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3092 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3082 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3038 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3028 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2986 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2976 | `NODE_ENV=test mocha test/**/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2959 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2951 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2929 | `nyc mocha && tsc` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2929 | `mocha test/*.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2906 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2902 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2859 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2855 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2835 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2817 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2811 | `mocha test/index.js && npm run demo` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2811 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2808 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2806 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2804 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2803 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2796 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2772 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2765 | `mocha --require should --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2756 | `istanbul cover _mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2751 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2746 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2729 | `NODE_ENV=test mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2728 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2725 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2722 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2722 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2716 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2701 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2692 | `mocha --opts mocha.opts` | 
| [tj/should.js](https://github.com/tj/should.js) | 2682 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2682 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2658 | `xo && mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2654 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2629 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2616 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [css/csso](https://github.com/css/csso) | 2613 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2613 | `npm run mocha && npm run lint` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2604 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2594 | `mocha-phantomjs ./test/index.html` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2593 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2587 | `mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2581 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2576 | `mocha --compilers js:babel-register --recursive spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2572 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2568 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2563 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2547 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2525 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2522 | `export TESTING=true; mocha --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2494 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2452 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2441 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2440 | `mocha --reporter=spec test/*-test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2435 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2421 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2418 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2414 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2399 | `export TESTING=true; mocha --reporter list` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2390 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2375 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2356 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2343 | `mocha test/src/**/*.unit.js` | 
| [json5/json5](https://github.com/json5/json5) | 2338 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2335 | `mocha --no-colors --reporter spec` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2335 | `mocha test` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2335 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2334 | `grunt jshint && mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2307 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2298 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2286 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2274 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2269 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2261 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2250 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2243 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2226 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2219 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2217 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2207 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2205 | `mocha -R spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2182 | `mocha test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2155 | `mocha --compilers js:babel-register` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2136 | `mocha -R landing test/index` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2129 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2080 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2066 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2062 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2062 | `mocha -R spec test/*.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2062 | `mocha && eslint .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2056 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2042 | `mocha test && npm run lint` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2019 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1983 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1960 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1947 | `mocha --compilers js:babel-register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1938 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1937 | `mocha --require=test/test_helper.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1933 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1908 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1907 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1904 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1900 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1896 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1895 | `mocha test/runner.js --reporter spec` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1866 | `mocha --reporter spec --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1865 | `mocha --require ./test/common --growl test/expect.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1862 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1858 | `mocha tests.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1854 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1854 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1828 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1823 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [then/promise](https://github.com/then/promise) | 1819 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1810 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1797 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1796 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1794 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1791 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1784 | `mocha && eslint *.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1781 | `mocha test/*.test.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1776 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1773 | `npm run lint && mocha -R dot && npm run cover` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1764 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1763 | `mocha test` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1760 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1760 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1745 | `npm run lint && mocha --reporter spec test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1742 | `nyc npm run _mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1735 | `mocha test/**/*_test.js --bail` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1734 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1731 | `mocha --reporter spec && npm run test-typescript` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1729 | `mocha test` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1728 | `mocha -R spec spec spec/reporters` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1727 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1724 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1719 | `npm run mocha && npm run karma` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1716 | `rm -rf ./dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1710 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1707 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1696 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1677 | `./node_modules/.bin/mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1677 | `npm run lint && npm run mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1675 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1674 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1670 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1658 | `mocha && npm run lint` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1656 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1645 | `npm run lint && npm run mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1644 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1631 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1630 | `mocha tests --compilers js:babel-core/register` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1619 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1618 | `mocha tests/test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1611 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1607 | `mocha test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1607 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1602 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1601 | `mocha test -u bdd -R spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1600 | `mocha --reporter spec test/*.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1598 | `standard "src/*.js" && npm run build && mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1597 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1589 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1583 | `eslint . && mocha -t 5000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1581 | `mocha test --timeout 600000` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1579 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1576 | `mocha ./test/basic.js -t 5000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1573 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1562 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1555 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1535 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1523 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1516 | `mocha --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1505 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1504 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1504 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1500 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1493 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1482 | `mocha --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1478 | `mocha -u tdd` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1475 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1468 | `mocha -R spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1462 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1461 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1447 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1443 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1442 | `mocha test/**/*.spec.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1439 | `eslint --cache . && tsc && mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1430 | `mocha --check-leaks -R dot` | 
| [teambit/bit](https://github.com/teambit/bit) | 1429 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1427 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1426 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1422 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1418 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1416 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1414 | `standard "./src/*.js" && mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1414 | `mocha test.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1408 | `mocha test.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1407 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1396 | `mocha tests.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1392 | `mocha compiled_tests/` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1389 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1383 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1379 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1378 | `mocha --check-leaks --reporter spec --bail` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1369 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1361 | `mocha test/setup.js test/spec/*.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1357 | `./node_modules/mocha/bin/mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1354 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1346 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1345 | `nyc npm run mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1336 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1334 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1317 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1314 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1304 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1291 | `mocha-phantomjs tests/index.html` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1279 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1277 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1277 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1274 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1269 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1268 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1265 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1260 | `mocha spec/exec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1252 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1246 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1236 | `mocha --check-leaks --require @babel/register` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1232 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1231 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1229 | `mocha test/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1229 | `mocha --recursive` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1223 | `mocha --opts test/opts/mocha.opts` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1222 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1220 | `mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1204 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1202 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1201 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1199 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1198 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1197 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1193 | `mocha test/**/*Spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1187 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1184 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1181 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1180 | `mocha test/unit` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1178 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1177 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1176 | `mocha test` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1175 | `standard && istanbul cover _mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1174 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1171 | `eslint src && mocha && karma start --single-run` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1170 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1169 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1168 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1166 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1165 | `mocha` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1162 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1160 | `mocha --reporter dot` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1147 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1141 | `node_modules/.bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1139 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1139 | `mocha --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1138 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1135 | `mocha src/test.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1135 | `nyc mocha --timeout=20000 test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1130 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1130 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1128 | `npm run lint && npm run mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1126 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1125 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1123 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1117 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1107 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1106 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1099 | `mocha tests/test-*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1095 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1094 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1092 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1086 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1086 | `mocha --check-leaks --reporter spec --bail test/` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1082 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1079 | `mocha test/*` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1074 | `mocha $(find test -name '*.test.js')` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1074 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1070 | `xo && mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1059 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1054 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1044 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1041 | `istanbul cover _mocha test/*.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1039 | `npm run prepublishOnly && mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1039 | `istanbul test _mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1038 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1034 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1030 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1022 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1021 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1020 | `mocha -R spec ./test/unit/**` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1020 | `mocha test/tests.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1017 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1010 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1010 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1009 | `mocha --recursive test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1006 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 996 | `mocha --compilers js:babel-core/register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 996 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 996 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 995 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 993 | `standard && mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 993 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 992 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 991 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 988 | `mocha tests/*.js` | 
| [router5/router5](https://github.com/router5/router5) | 987 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 980 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 976 | `mocha ./test/test*.js --reporter spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 973 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 973 | `mocha $(find test -name '*.test.js')` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 971 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 966 | `mocha -t 120000 test/*.test.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 966 | `webpack && mocha test/unit` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 963 | `mocha -R list` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 961 | `mocha --recursive test/unit/` | 
| [electron/asar](https://github.com/electron/asar) | 961 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 960 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 959 | `mocha test` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 958 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 956 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 955 | `mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 950 | `mocha --timeout 5000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 949 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 949 | `standard && mocha -b` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 946 | `mocha --reporter spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 945 | `mocha && standard` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 940 | `npm run lint && npm run mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 940 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 934 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 931 | `eslint src test && mocha --compilers babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 929 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 923 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 917 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 916 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 913 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 909 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 904 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 904 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 903 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 903 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 903 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 901 | `TEST=all mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 901 | `npm run lint && mocha --require @babel/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 893 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 886 | `mocha --compilers js:babel-register test/*.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 884 | `mocha ./test -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 883 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 882 | `mocha --reporter spec --bail --check-leaks test/` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 879 | `npm run convertto:es5 && npm run mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 879 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 877 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 875 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 870 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 866 | `npm run lint && mocha -R spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 866 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 857 | `mocha tests` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 856 | `mocha -R spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 856 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 855 | `node_modules/.bin/mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 855 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 850 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 850 | `mocha --timeout 20000` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 846 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 845 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 845 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 844 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 844 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 842 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 841 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 834 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 826 | `npm run mocha:istanbul` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 825 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 822 | `mocha -t 600000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 821 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 820 | `mocha --check-leaks -t 20000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 818 | `mocha --reporter spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 816 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 815 | `istanbul cover _mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 815 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 813 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 812 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 810 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 809 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 805 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 804 | `nyc mocha specs` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 803 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 802 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 801 | `mocha -t 5000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 798 | `mocha test --compilers js:babel-register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 798 | `mocha --require babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 795 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 793 | `mocha --reporter spec --bail --check-leaks test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 792 | `istanbul cover -- _mocha --reporter spec` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 789 | `cake build && mocha ./test/mocha/*.coffee` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 788 | `mocha spec/*.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 787 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 787 | `./node_modules/.bin/mocha -R spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 786 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 783 | `mocha --reporter list` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 783 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 779 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 777 | `mocha --colors --reporter spec test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 774 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 772 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 771 | `mocha --async-only` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 770 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 768 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 768 | `xo && mocha -R spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 767 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 767 | `npm run lint && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 758 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 757 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 753 | `mocha --ui tdd --require ./test/__setup` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 750 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 747 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 744 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 744 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 742 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 738 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 736 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 735 | `mocha --recursive -s 15 test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 734 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 733 | `npm run mocha-test test/integration` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 730 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 729 | `mocha test` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 726 | `mocha test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 721 | `mocha test --compilers js:babel-core/register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 718 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 718 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 718 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 716 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 716 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 716 | `npm run build && istanbul test _mocha test/test.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 715 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 715 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 714 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 713 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 713 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 713 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 712 | `mocha tests/*.mocha.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 711 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 711 | `nyc --check-coverage mocha test/*.test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 711 | `mocha --harmony --full-trace --check-leaks` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 711 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 708 | `mocha test` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 708 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 