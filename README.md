# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:59 03/26/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40187 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40040 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 37351 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29037 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23612 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22609 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21273 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 20743 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18142 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17816 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15806 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15229 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13920 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13500 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12927 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12340 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12206 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12058 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11904 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11807 | `mocha --reporter spec test/*-test.js` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11791 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11432 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10963 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10760 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10352 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9918 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9817 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9489 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9462 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9429 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9290 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9261 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8977 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8656 | `grunt mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8589 | `mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8513 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8303 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8207 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8205 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8130 | `grunt clean:test && mocha --exit` | 
| [websockets/ws](https://github.com/websockets/ws) | 8070 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8002 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7955 | `./node_modules/.bin/mocha test/src` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7831 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7816 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7797 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [amark/gun](https://github.com/amark/gun) | 7788 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7590 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7478 | `mocha tests/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7470 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7247 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7227 | `npm run build && istanbul cover _mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7146 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7104 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6924 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6622 | `nyc mocha test/**/* -r ./test/before` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6615 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6595 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6568 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6565 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6525 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6478 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6478 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6415 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6033 | `npm run lint -s && npm run mocha -s` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6020 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6006 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5954 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5926 | `mocha` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5912 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5834 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5652 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5580 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5559 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5485 | `mocha test/test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5473 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5434 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5361 | `mocha --exit --require babel-core/register` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5249 | `npm run build-cli && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5230 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5186 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5143 | `mocha src/**/*Tests.js --harmony` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5100 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4880 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4801 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4782 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4755 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4721 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4691 | `mocha; jshint *.js lib` | 
| [santinic/how2](https://github.com/santinic/how2) | 4654 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4638 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4634 | `mocha --reporter spec -t 8000` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4624 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4621 | `standard && mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4542 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4536 | `mocha ./test/runner.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4532 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4489 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4453 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4419 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4395 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4394 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4315 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4275 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4263 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4249 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4242 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4032 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4001 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3930 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3924 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3893 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [muicss/mui](https://github.com/muicss/mui) | 3892 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3867 | `npm run lint && npm run mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3858 | `export TESTING=true; mocha --reporter list` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3831 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3817 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3813 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3737 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3717 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3693 | `npm run lint ; mocha && mocha test/individual` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3683 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3645 | `npm run jshint && npm run mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3644 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3640 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3640 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3573 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3570 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3550 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3544 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3506 | `npm run build && mocha test/*.test.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3479 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3474 | `npm run lint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3471 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3443 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3423 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3409 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3403 | `mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3380 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3380 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3355 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3257 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3235 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3226 | `nyc mocha "test/**/*.test.js"` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3213 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3188 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3170 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3101 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3082 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3082 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3077 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3068 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3011 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3004 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3003 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2979 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2939 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2916 | `mocha test/*.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2915 | `NODE_ENV=test mocha test/**/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2896 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2883 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2866 | `nyc mocha && tsc` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2847 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2805 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2804 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2795 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2790 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2785 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2784 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2782 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2779 | `mocha -R spec --recursive src/test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2775 | `mocha test/index.js && npm run demo` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2763 | `mocha --require should --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2756 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2750 | `istanbul cover _mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2738 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2730 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2722 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [github-tools/github](https://github.com/github-tools/github) | 2709 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2704 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2703 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2694 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2687 | `mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2674 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2666 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2664 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2654 | `mocha --opts mocha.opts` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2645 | `xo && mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2630 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2621 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2602 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2601 | `mocha --reporter dot` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2598 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2591 | `mocha-phantomjs ./test/index.html` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2588 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2564 | `mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2547 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2539 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2538 | `mocha --compilers js:babel-register --recursive spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2536 | `mocha --recursive --watch` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2530 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2522 | `yarn tsc && yarn lint && mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2521 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2519 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2492 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2478 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2450 | `NODE_ENV=test mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2433 | `mocha --reporter=spec test/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2419 | `node_modules/.bin/mocha --reporter spec` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2415 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2413 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2400 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2383 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2383 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2355 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2352 | `npm run build && cd test && mocha . --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2345 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2335 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2335 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2334 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2329 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2319 | `mocha test` | 
| [json5/json5](https://github.com/json5/json5) | 2293 | `nyc --reporter=html --reporter=text mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2269 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2258 | `mocha --require should --reporter spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2250 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2249 | `mocha "test/**/*-test.js"` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2240 | `mocha test/unit --require mochahook` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2240 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2228 | `npm run lint && npm run build && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2228 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2222 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2217 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2216 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2209 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2191 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2190 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2148 | `mocha --compilers js:babel-register` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2141 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2128 | `mocha test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2096 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2086 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2085 | `mocha -R landing test/index` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2073 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2057 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2053 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2039 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2035 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2034 | `mocha && eslint .` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2008 | `mocha test && npm run lint` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1970 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1969 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1950 | `standard && mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1934 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1925 | `mocha -c test/index.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1918 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1913 | `mocha --compilers js:babel-register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1905 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1902 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1898 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1891 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1876 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1862 | `mocha --require ./test/common --growl test/expect.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1861 | `mocha test/runner.js --reporter spec` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1858 | `mocha --reporter spec --timeout 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1851 | `mocha tests.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1835 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1834 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1820 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1811 | `cross-env NODE_ENV=test mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1809 | `mocha --compilers js:babel-core/register __tests__` | 
| [then/promise](https://github.com/then/promise) | 1806 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1797 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1791 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1786 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1784 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1781 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1768 | `mocha test/*.test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1758 | `mocha test` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1757 | `npm run lint && mocha -R dot && npm run cover` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1755 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1753 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1752 | `./node_modules/.bin/mocha && npm run jshint` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1751 | `mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1742 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1731 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1730 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1723 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1718 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1715 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1714 | `mocha -R spec spec spec/reporters` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1713 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1712 | `nyc npm run _mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1709 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1706 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1702 | `npm run mocha && npm run karma` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1700 | `npm run lint && mocha server/test --timeout 10000 --recursive --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1698 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1691 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1673 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1671 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1670 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1655 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1648 | `mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1642 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1640 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1638 | `mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1624 | `mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1615 | `mocha tests/test.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1612 | `mocha --reporter spec --grep .` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1612 | `mocha --expose-gc --slow 300` | 
| [pahen/madge](https://github.com/pahen/madge) | 1608 | `npm run lint && npm run mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1608 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1605 | `mocha tests --compilers js:babel-core/register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1598 | `mocha test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1594 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1589 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1583 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1578 | `mocha test/**/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1578 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1577 | `mocha test -u bdd -R spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1570 | `mocha --reporter spec test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1567 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1564 | `mocha ./test/basic.js -t 5000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1557 | `standard "src/*.js" && npm run build && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1557 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1548 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1546 | `mocha spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1514 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1511 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1503 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1502 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1500 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1493 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1488 | `mocha --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1481 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1479 | `mocha -u tdd` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1471 | `mocha --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1469 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1458 | `node_modules/.bin/mocha --recursive` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1456 | `eslint . && mocha -t 5000` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1442 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [samccone/drool](https://github.com/samccone/drool) | 1441 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1441 | `mocha test/**/*.spec.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1437 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1436 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1423 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1416 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1413 | `nyc mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1411 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1409 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1408 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1408 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1395 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1394 | `standard "./src/*.js" && mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1375 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1370 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1369 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1369 | `mocha --recursive` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1368 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1368 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [zeit/ms](https://github.com/zeit/ms) | 1362 | `mocha tests.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1362 | `mocha compiled_tests/` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1361 | `mocha --check-leaks --reporter spec --bail` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1354 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1336 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1334 | `istanbul cover _mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1333 | `mocha test/setup.js test/spec/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1332 | `mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1324 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1320 | `nyc npm run mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1317 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1308 | `mocha --timeout 10000 ./tests/lib.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1302 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1296 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1295 | `mocha-phantomjs tests/index.html` | 
| [noble/bleno](https://github.com/noble/bleno) | 1294 | `mocha -R spec test/*.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1267 | `./node_modules/.bin/mocha test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1263 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1263 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1258 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1258 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1258 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1250 | `mocha spec/exec.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1246 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1243 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1230 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1229 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1225 | `mocha --check-leaks --require @babel/register` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1222 | `mocha test/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1218 | `mocha --recursive` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1215 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1211 | `mocha tests` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1210 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1203 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1199 | `mocha --opts test/opts/mocha.opts` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1196 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1196 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1193 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1193 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1187 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1184 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1176 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1175 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1174 | `node ./node_modules/mocha/bin/mocha tests` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1174 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1169 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1158 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1157 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1156 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1153 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1151 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1150 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1150 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1149 | `standard && istanbul cover _mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1144 | `mocha test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1142 | `mocha --reporter dot` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1131 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1130 | `eslint src && mocha && karma start --single-run` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1129 | `node_modules/.bin/mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1128 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [normalize/mz](https://github.com/normalize/mz) | 1127 | `mocha --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1125 | `mocha src/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1123 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1120 | `npm run lint && npm run mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1119 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1119 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1118 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1111 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1100 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1100 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1099 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1096 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1094 | `nyc mocha --timeout=20000 test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1091 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1090 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1086 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1076 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1070 | `mocha test/*` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1067 | `mocha $(find test -name '*.test.js')` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1067 | `mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1067 | `mocha tests/test-*` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1065 | `mocha --check-leaks --reporter spec --bail test/` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1063 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1051 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1042 | `mocha --reporter spec --timeout 3000` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1041 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1039 | `istanbul test _mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1033 | `istanbul cover _mocha test/*.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1032 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1031 | `NODE_PATH=. mocha **/*.spec.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1027 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1027 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1020 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1019 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1016 | `mocha --check-leaks -R dot` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1013 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1012 | `npm run prepublishOnly && mocha test/test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1012 | `mocha test/tests.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1004 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1001 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 997 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 996 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 992 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 989 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 989 | `standard && mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 983 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 982 | `mocha --compilers js:babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 980 | `mocha --recursive test` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 977 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 976 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 974 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 972 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 971 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 970 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 969 | `mocha -R spec ./test/unit/**` | 
| [router5/router5](https://github.com/router5/router5) | 969 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 960 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 960 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 960 | `mocha -R list` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 959 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 956 | `mocha --async-only` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 956 | `mocha -t 120000 test/*.test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 955 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 953 | `webpack && mocha test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 952 | `mocha tests/*.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 951 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 951 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 947 | `mocha ./test/test*.js --reporter spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 945 | `mocha --reporter spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 943 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 942 | `standard && mocha -b` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 935 | `nyc mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 932 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 931 | `mocha && standard` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 930 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 926 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 923 | `npm run lint && npm run mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 922 | `eslint src test && mocha --compilers babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 919 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 916 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 913 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 912 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 906 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 898 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 894 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 893 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 893 | `mocha "client.test" --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 889 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 888 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 882 | `mocha --compilers js:babel-register test/*.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 878 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 877 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 874 | `mocha --reporter spec --bail --check-leaks test/` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 873 | `npm run lint && mocha --require @babel/register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 871 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 869 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 869 | `mocha --reporter list` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 868 | `mocha ./test -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 867 | `mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 866 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 866 | `npm run convertto:es5 && npm run mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 856 | `npm run lint && mocha -R spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 853 | `node_modules/.bin/mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 850 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 849 | `mocha tests` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 844 | `npm run lint && npm run mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 843 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 840 | `mocha -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 839 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 839 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 838 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 837 | `node_modules/.bin/mocha test/spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 837 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 837 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 833 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 825 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 824 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 821 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 820 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 820 | `mocha && ember test` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 817 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 816 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 814 | `mocha --check-leaks -t 20000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 812 | `standard && standard ./bin/* && mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 811 | `mocha -t 600000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 811 | `mocha --timeout 20000` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 808 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 806 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 804 | `istanbul cover _mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 804 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 804 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 800 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 799 | `mocha test --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 799 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 799 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 798 | `mocha --require babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 793 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 793 | `mocha -t 5000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 791 | `npm run mocha:istanbul` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 791 | `nyc mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 788 | `cake build && mocha ./test/mocha/*.coffee` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 788 | `nyc mocha specs` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 786 | `istanbul cover -- _mocha --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 785 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 782 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 781 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 778 | `./node_modules/.bin/mocha -R spec` | 
| [edsu/anon](https://github.com/edsu/anon) | 777 | `mocha --colors --reporter spec test.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 776 | `mocha spec/*.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 775 | `mocha --reporter list` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 771 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 769 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 768 | `mocha --async-only` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 767 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 767 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 766 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 765 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 761 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 755 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 755 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 754 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 747 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 743 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 741 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 738 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 735 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 734 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 734 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 730 | `mocha --recursive -s 15 test/` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 730 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 729 | `mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 728 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 725 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 723 | `npm run mocha-test test/integration` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 722 | `mocha test.js` | 
| [developit/decko](https://github.com/developit/decko) | 715 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 714 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 713 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 713 | `mocha test` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 712 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 712 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 712 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 711 | `npm run build && istanbul test _mocha test/test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 710 | `mocha` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 709 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 707 | `mocha tests/*.mocha.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 706 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 706 | `mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 705 | `npm run bundle && mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 704 | `mocha --harmony --full-trace --check-leaks` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 704 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 703 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 702 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 700 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 699 | `mocha test` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 699 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 