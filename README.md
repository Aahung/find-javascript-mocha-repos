# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:59 03/16/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39992 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39937 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 37176 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28976 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23547 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22481 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21120 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 20467 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18041 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17741 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15717 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15121 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13890 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13391 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12846 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12253 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12176 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12040 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11854 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11779 | `mocha --reporter spec test/*-test.js` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11661 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11327 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10810 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10726 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10245 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9839 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9734 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9433 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9418 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9383 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9241 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9192 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8949 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8622 | `grunt mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8494 | `mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8472 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8203 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8197 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8168 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8108 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7960 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [websockets/ws](https://github.com/websockets/ws) | 7953 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7908 | `./node_modules/.bin/mocha test/src` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7803 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7782 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7730 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7678 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7509 | `npm run eslint && npm run mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7465 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7420 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7207 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7207 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7056 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7037 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6845 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6602 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6561 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6533 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6529 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6521 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6480 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6419 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6410 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6381 | `mocha --compilers js:babel-core/register` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6006 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6006 | `npm run lint -s && npm run mocha -s` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5927 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5924 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5911 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5870 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5779 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5614 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5544 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5537 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5449 | `mocha && eslint lib/**` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5430 | `mocha test/test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5407 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5394 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5287 | `mocha --exit --require babel-core/register` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5172 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5162 | `mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5141 | `mocha src/**/*Tests.js --harmony` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5113 | `npm run build-cli && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5056 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4828 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4792 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4759 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4755 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4687 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4643 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4634 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4627 | `mocha --reporter spec -t 8000` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4576 | `standard && mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4548 | `mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4534 | `mocha ./test/runner.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4529 | `mocha; jshint *.js lib` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4528 | `gulp build; mocha;` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4468 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4460 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4434 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4395 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4380 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4372 | `./node_modules/.bin/mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4239 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4236 | `mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4235 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4226 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4108 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4019 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3965 | `mocha --recursive && make test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3917 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3894 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3888 | `NODE_ENV=test mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3876 | `mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3854 | `export TESTING=true; mocha --reporter list` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3838 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3809 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3805 | `mocha --require should --reporter spec` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3794 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3702 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3701 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3667 | `npm run lint ; mocha && mocha test/individual` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3640 | `npm run jshint && npm run mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3626 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3620 | `mocha ./test/*.spec.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3609 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3576 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3562 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3547 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3545 | `mocha tests/javascript` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3531 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3493 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3461 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3442 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3427 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3414 | `node_modules/.bin/mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3407 | `npm run lint && npm run mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3404 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3399 | `mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3371 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3354 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3317 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3236 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3208 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3190 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3186 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3151 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3131 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3101 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3075 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3072 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3068 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3035 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3015 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2990 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2989 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2978 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2963 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2938 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2904 | `mocha test/*.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2886 | `NODE_ENV=test mocha test/**/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2862 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2851 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2833 | `nyc mocha && tsc` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2802 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2798 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2790 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2781 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2773 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2772 | `mocha -R spec --recursive src/test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2767 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2761 | `mocha test/index.js && npm run demo` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2759 | `mocha --require should --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2755 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2751 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2743 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2743 | `istanbul cover _mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2710 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2706 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2702 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [github-tools/github](https://github.com/github-tools/github) | 2698 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2690 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2681 | `mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2675 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2663 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2661 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2648 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2643 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2635 | `xo && mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2630 | `mocha --opts mocha.opts` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2617 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2606 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2597 | `mocha --timeout 100000` | 
| [css/csso](https://github.com/css/csso) | 2592 | `mocha --reporter dot` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2584 | `mocha-phantomjs ./test/index.html` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2584 | `npm run mocha && npm run lint` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2561 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2551 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2530 | `mocha --compilers js:babel-register --recursive spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2529 | `mocha --recursive --watch` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2523 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2519 | `export TESTING=true; mocha --reporter list` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2512 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2511 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2510 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2485 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2467 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2461 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2432 | `mocha --reporter=spec test/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2423 | `NODE_ENV=test mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2405 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2395 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2388 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2377 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2362 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2351 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2343 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2340 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2338 | `npm run build && cd test && mocha . --reporter dot` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2333 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2332 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2326 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2320 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2311 | `mocha test` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2301 | `npm run lint && mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2273 | `nyc --reporter=html --reporter=text mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2266 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2262 | `export TESTING=true; mocha --reporter list` | 
| [mde/ejs](https://github.com/mde/ejs) | 2236 | `mocha --require should --reporter spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2234 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2231 | `mocha "test/**/*-test.js"` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2229 | `mocha test test/unit/**/*_test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2227 | `mocha test/unit --require mochahook` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2220 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2215 | `npm run lint && npm run build && npm run mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2215 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2213 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2206 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2203 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2178 | `mocha -R spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2175 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [gajus/swing](https://github.com/gajus/swing) | 2142 | `mocha --compilers js:babel-register` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2109 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2096 | `mocha test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2090 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2084 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2067 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2051 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2048 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2043 | `mocha -R landing test/index` | 
| [noble/noble](https://github.com/noble/noble) | 2026 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2022 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2022 | `mocha && eslint .` | 
| [slate/slate](https://github.com/slate/slate) | 2013 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1981 | `mocha test && npm run lint` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1945 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1938 | `standard && mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1935 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1914 | `mocha -c test/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1914 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1906 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1900 | `mocha --bail --reporter spec --check-leaks test/` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1899 | `mocha test/index.js --reporter dot` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1890 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1885 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1884 | `mocha --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1863 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1857 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1851 | `mocha tests.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1849 | `mocha --reporter spec --timeout 5000` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1840 | `mocha test/runner.js --reporter spec` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1826 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1819 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1804 | `cross-env NODE_ENV=test mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1793 | `mocha --compilers js:babel-core/register __tests__` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1792 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1791 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [then/promise](https://github.com/then/promise) | 1791 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1784 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1779 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1778 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1773 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1756 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1755 | `mocha test/*.test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1746 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1740 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1737 | `npm run lint && mocha -R dot && npm run cover` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1733 | `mocha && eslint *.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1729 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1719 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1715 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1712 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1711 | `mocha -R spec spec spec/reporters` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1708 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1707 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1706 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1698 | `mocha --reporter spec && npm run test-typescript` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1695 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1692 | `npm run lint && mocha server/test --recursive --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1691 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1690 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1688 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1687 | `nyc npm run _mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1669 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1668 | `./node_modules/.bin/mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1664 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1650 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1636 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1629 | `mocha && npm run lint` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1626 | `mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1614 | `mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1613 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1609 | `mocha --expose-gc --slow 300` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1606 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1602 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1601 | `mocha --reporter spec --grep .` | 
| [pahen/madge](https://github.com/pahen/madge) | 1592 | `npm run lint && npm run mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1592 | `mocha test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1589 | `mocha tests --compilers js:babel-core/register` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1585 | `npm run lint && mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1582 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1579 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1574 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1572 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1569 | `mocha test/**/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1554 | `mocha ./test/basic.js -t 5000` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1552 | `mocha --reporter spec test/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1545 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1541 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1539 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1538 | `mocha spec` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1528 | `standard "src/*.js" && npm run build && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1510 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1507 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1502 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1498 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1497 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1485 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1480 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1474 | `mocha -u tdd` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1469 | `mocha --compilers js:babel-register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1469 | `mocha -R spec` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1462 | `mocha --reporter spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1457 | `node_modules/.bin/mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1438 | `mocha test/tests.js --timeout=10000` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1434 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1426 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1423 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1422 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1412 | `eslint --cache . && tsc && mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1410 | `mocha test.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1408 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1407 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1405 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1403 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1402 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1400 | `eslint . && mocha -t 5000` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1391 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1386 | `standard "./src/*.js" && mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1368 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1367 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1363 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1363 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1354 | `./node_modules/mocha/bin/mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1354 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1353 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1353 | `mocha --check-leaks --reporter spec --bail` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1344 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1335 | `mocha compiled_tests/` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1333 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1330 | `istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1323 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1320 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1316 | `mocha test/setup.js test/spec/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1309 | `nyc npm run mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1299 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1296 | `mocha --timeout 10000 ./tests/lib.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1295 | `mocha-phantomjs tests/index.html` | 
| [noble/bleno](https://github.com/noble/bleno) | 1289 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1288 | `npm run build && mocha -r should` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1264 | `./node_modules/.bin/mocha test` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1255 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1251 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1251 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1250 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1250 | `mocha spec/exec.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1248 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1239 | `istanbul cover _mocha test -- --timeout 20000` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1226 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1225 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1221 | `mocha test/*.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1221 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1217 | `mocha --check-leaks --require @babel/register` | 
| [teambit/bit](https://github.com/teambit/bit) | 1212 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1212 | `mocha --recursive` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1211 | `mocha tests` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1211 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1199 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1199 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1196 | `mocha test/**/*Spec.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1192 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1190 | `mocha --opts test/opts/mocha.opts` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1190 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1189 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1183 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1180 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1172 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1172 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1169 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1167 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1155 | `mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1151 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1151 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1150 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1142 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1135 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1135 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1135 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1132 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1127 | `mocha --reporter dot` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1122 | `mocha test` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1118 | `node_modules/.bin/mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1117 | `npm run lint && npm run mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1116 | `mocha src/test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1115 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1115 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1115 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1115 | `mocha --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1115 | `eslint src && mocha && karma start --single-run` | 
| [variety/variety](https://github.com/variety/variety) | 1114 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1109 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1109 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1100 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1098 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1090 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1089 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1088 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1087 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1085 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1077 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1068 | `mocha test/*` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1067 | `nyc mocha --timeout=20000 test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1066 | `mocha $(find test -name '*.test.js')` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1064 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1061 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1061 | `xo && mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1054 | `mocha --check-leaks --reporter spec --bail test/` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1053 | `mocha tests/test-*` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1048 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1044 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1036 | `istanbul test _mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1031 | `istanbul cover _mocha test/*.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1030 | `NODE_PATH=. mocha **/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1024 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1022 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1019 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1017 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1015 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1011 | `mocha test/tests.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1010 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1006 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 997 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 996 | `npm run prepublishOnly && mocha test/test.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 996 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 996 | `mocha --colors ./test/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 991 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 984 | `standard && mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 982 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 981 | `mocha --recursive --bail --reporter spec test` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 979 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 972 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 971 | `mocha --recursive test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 970 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 969 | `mocha --compilers js:babel-core/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 965 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 959 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 959 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 958 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 958 | `mocha -R list` | 
| [router5/router5](https://github.com/router5/router5) | 958 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 956 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 953 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 952 | `mocha --async-only` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 951 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 949 | `mocha -t 120000 test/*.test.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 948 | `mocha test` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 946 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 946 | `mocha --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 945 | `mocha -R spec ./test/unit/**` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 945 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 945 | `webpack && mocha test/unit` | 
| [electron/asar](https://github.com/electron/asar) | 944 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 939 | `mocha tests/*.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 939 | `standard && mocha -b` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 933 | `mocha ./test/test*.js --reporter spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 933 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 929 | `nyc mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 923 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 918 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 916 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 916 | `eslint src test && mocha --compilers babel-register` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 914 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 907 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 906 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 905 | `npm run lint && npm run mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 901 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 897 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 896 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 894 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 891 | `mocha "client.test" --compilers js:babel-register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 887 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 886 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 880 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 875 | `mocha --compilers js:babel-register test/*.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 874 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 869 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 869 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 867 | `mocha --reporter list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 865 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 864 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 863 | `npm run lint && mocha --require @babel/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 860 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 859 | `npm run convertto:es5 && npm run mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 858 | `mocha ./test -R spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 852 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 851 | `node_modules/.bin/mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 850 | `npm run lint && mocha -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 848 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 842 | `npm run lint && npm run mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 841 | `mocha tests` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 837 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 837 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 835 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 832 | `node_modules/.bin/mocha test/spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 830 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 830 | `mocha -R spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 830 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 819 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 817 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 817 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 816 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 814 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 813 | `mocha --check-leaks -t 20000` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 807 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 807 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 806 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 806 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 804 | `istanbul cover _mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 804 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 803 | `mocha -t 600000` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 800 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 800 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 800 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 796 | `mocha --require babel-register` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 796 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 795 | `mocha test --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 795 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 792 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 789 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 788 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 787 | `nyc mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 787 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 784 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 784 | `nyc mocha specs` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 783 | `istanbul cover -- _mocha --reporter spec` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 780 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 778 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [edsu/anon](https://github.com/edsu/anon) | 777 | `mocha --colors --reporter spec test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 777 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 776 | `npm run mocha:istanbul` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 773 | `mocha --reporter list` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 773 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 772 | `./node_modules/.bin/mocha -R spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 770 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 765 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 765 | `mocha --async-only` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 763 | `xo && mocha -R spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 761 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 761 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 754 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 750 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 743 | `mocha -R spec src/**/*_test.js` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 743 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 739 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 737 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 734 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 732 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 730 | `mocha --recursive -s 15 test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 728 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 727 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 725 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 722 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 722 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 722 | `mocha test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 719 | `npm run mocha-test test/integration` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 714 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 711 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [developit/decko](https://github.com/developit/decko) | 710 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 710 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 708 | `mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 707 | `npm run build && istanbul test _mocha test/test.js` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 707 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 706 | `mocha tests/*.mocha.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 703 | `npm run bundle && mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 703 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 699 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 699 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 698 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 697 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 696 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 696 | `mocha --harmony --full-trace --check-leaks` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 695 | `mocha test` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 695 | `mocha --timeout 20000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 694 | `mocha test` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 