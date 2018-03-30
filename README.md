# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:58 03/30/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40298 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40067 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 37415 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29080 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23653 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22666 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21344 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 20895 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18205 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17864 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15844 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15266 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13934 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13576 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12966 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12366 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12222 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12071 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11927 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11858 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11822 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11507 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11034 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10782 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10407 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9956 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9860 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9527 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9476 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9450 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9327 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9300 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8993 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8674 | `grunt mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8636 | `mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8530 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8340 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8216 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8212 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8135 | `grunt clean:test && mocha --exit` | 
| [websockets/ws](https://github.com/websockets/ws) | 8118 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8022 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7974 | `./node_modules/.bin/mocha test/src` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7842 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7840 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7827 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [amark/gun](https://github.com/amark/gun) | 7817 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7611 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7514 | `mocha tests/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7474 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7272 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7236 | `npm run build && istanbul cover _mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7180 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7142 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6975 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6674 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6656 | `mocha --opts mocha.opts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6619 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6617 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6587 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6548 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6532 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6513 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6432 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6108 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6043 | `npm run lint -s && npm run mocha -s` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6008 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5965 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5940 | `npm run test:mocha:src` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5924 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5850 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5677 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5602 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5569 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5506 | `mocha test/test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5486 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5450 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5396 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5389 | `mocha --exit --require babel-core/register` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5323 | `npm run build-cli && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5257 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5194 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5145 | `mocha src/**/*Tests.js --harmony` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5119 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4902 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4804 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4792 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4756 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4751 | `mocha; jshint *.js lib` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4735 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4682 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4666 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4644 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4639 | `mocha --reporter spec -t 8000` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4638 | `standard && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4563 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4545 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4537 | `mocha ./test/runner.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4529 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4463 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4441 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4402 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4399 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4315 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4301 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4277 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4252 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4251 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4035 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4025 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3943 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3931 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3901 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3881 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3866 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3858 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3821 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3814 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3748 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3726 | `nyc mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3704 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3703 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3701 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3647 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3647 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3646 | `npm run jshint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3592 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3572 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3552 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3547 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3506 | `npm run build && mocha test/*.test.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3496 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3495 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3474 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3443 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3429 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3411 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3407 | `mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3393 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3389 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3374 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3270 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3251 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3235 | `nyc mocha "test/**/*.test.js"` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3221 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3207 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3176 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3102 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3091 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3087 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3086 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3085 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3080 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3032 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3013 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3013 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2982 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2942 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2933 | `NODE_ENV=test mocha test/**/*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2918 | `mocha test/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2911 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2885 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2885 | `nyc mocha && tsc` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2860 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2821 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2812 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2810 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2803 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2796 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2793 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2790 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2781 | `mocha -R spec --recursive src/test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2780 | `mocha test/index.js && npm run demo` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2763 | `mocha --require should --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2761 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2754 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2752 | `istanbul cover _mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2739 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2728 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2712 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2711 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2707 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2703 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2698 | `mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2676 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2674 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2669 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2666 | `mocha --opts mocha.opts` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2648 | `xo && mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2638 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2626 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2608 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2604 | `mocha --reporter dot` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2600 | `mocha --timeout 100000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2593 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2592 | `mocha-phantomjs ./test/index.html` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2576 | `yarn tsc && yarn lint && mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2572 | `mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2559 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2556 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2541 | `mocha --compilers js:babel-register --recursive spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2537 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2537 | `mocha --recursive --watch` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2526 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2523 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2511 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2485 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2463 | `NODE_ENV=test mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2435 | `mocha --reporter=spec test/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2428 | `node_modules/.bin/mocha --reporter spec` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2418 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2418 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2405 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2403 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2389 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2370 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2369 | `npm run build && cd test && mocha . --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2349 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2336 | `mocha test/src/**/*.unit.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2335 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2335 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2335 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2324 | `mocha test` | 
| [json5/json5](https://github.com/json5/json5) | 2303 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2270 | `mocha --require should --reporter spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2270 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2260 | `mocha "test/**/*-test.js"` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2259 | `mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2252 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2250 | `mocha test/unit --require mochahook` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2231 | `npm run lint && npm run build && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2226 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2222 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2211 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2197 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2196 | `mocha -R spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2162 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2152 | `mocha --compilers js:babel-register` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2151 | `mocha test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2113 | `nyc --reporter=html --reporter=text mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2105 | `mocha -R landing test/index` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2087 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2074 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2057 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2055 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2046 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2044 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2044 | `mocha && eslint .` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2022 | `mocha test && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1981 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1970 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1954 | `standard && mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1933 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1928 | `mocha -c test/index.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1921 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1919 | `mocha --compilers js:babel-register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1906 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1902 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1901 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1892 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1886 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1871 | `mocha test/runner.js --reporter spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1863 | `mocha --require ./test/common --growl test/expect.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1863 | `mocha --reporter spec --timeout 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1850 | `mocha tests.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1841 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1840 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1832 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1816 | `mocha --compilers js:babel-core/register __tests__` | 
| [then/promise](https://github.com/then/promise) | 1814 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1807 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1791 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1790 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1789 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1786 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1772 | `mocha test/*.test.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1763 | `mocha && eslint *.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1761 | `npm run lint && mocha -R dot && npm run cover` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1760 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1760 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1759 | `mocha test` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1758 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1758 | `./node_modules/.bin/mocha && npm run jshint` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1737 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1732 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1727 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1725 | `mocha --reporter spec && npm run test-typescript` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1723 | `nyc npm run _mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1721 | `mocha -R spec spec spec/reporters` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1719 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1719 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1713 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1709 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1708 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1708 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1700 | `npm run lint && mocha server/test --timeout 10000 --recursive --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1691 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1674 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1672 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1671 | `npm run lint && npm run mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1657 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1657 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1648 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1642 | `mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1629 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1620 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1619 | `mocha --reporter spec --grep .` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1618 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1617 | `mocha tests/test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1608 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1608 | `mocha tests --compilers js:babel-core/register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1600 | `mocha test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1596 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1594 | `npm run lint && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1587 | `mocha test/**/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1585 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1582 | `mocha test -u bdd -R spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1580 | `mocha --reporter spec test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1578 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1573 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1568 | `mocha ./test/basic.js -t 5000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1565 | `standard "src/*.js" && npm run build && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1561 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1552 | `mocha test/* --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1548 | `mocha spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1519 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1513 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1503 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1503 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1501 | `./node_modules/mocha/bin/mocha -R spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1498 | `mocha --compilers js:babel-register` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1497 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1490 | `eslint . && mocha -t 5000` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1485 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1479 | `mocha -u tdd` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1473 | `mocha --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1469 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1459 | `node_modules/.bin/mocha --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1451 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1444 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1443 | `mocha test/tests.js --timeout=10000` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1442 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1442 | `mocha test/**/*.spec.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1426 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1419 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1416 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1416 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1412 | `mocha test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1412 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1409 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1402 | `standard "./src/*.js" && mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1399 | `mocha test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1382 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1381 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1380 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1373 | `mocha compiled_tests/` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1372 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1372 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zeit/ms](https://github.com/zeit/ms) | 1371 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1368 | `mocha --check-leaks --reporter spec --bail` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1368 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1356 | `./node_modules/mocha/bin/mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1340 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1337 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1336 | `mocha test/setup.js test/spec/*.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1335 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1334 | `istanbul cover _mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1333 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1330 | `nyc npm run mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1312 | `mocha --timeout 10000 ./tests/lib.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1299 | `npm run build && mocha -r should` | 
| [noble/bleno](https://github.com/noble/bleno) | 1296 | `mocha -R spec test/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1293 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1270 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1266 | `./node_modules/.bin/mocha test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1265 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1265 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1263 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1260 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1259 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1254 | `mocha spec/exec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1250 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1235 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1231 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1228 | `mocha --check-leaks --require @babel/register` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1224 | `mocha test/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1219 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1218 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1216 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1214 | `mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1211 | `mocha --opts test/opts/mocha.opts` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1203 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1198 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1197 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1194 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1194 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1189 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1187 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1184 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1177 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1176 | `node ./node_modules/mocha/bin/mocha tests` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1176 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1175 | `mocha test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1169 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1163 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1163 | `mocha test` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1161 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1160 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1160 | `standard && istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1157 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1157 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1155 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1155 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1152 | `eslint src && mocha && karma start --single-run` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1151 | `mocha --reporter dot` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1135 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [normalize/mz](https://github.com/normalize/mz) | 1133 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1132 | `node_modules/.bin/mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1131 | `mocha src/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1130 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1128 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1125 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [variety/variety](https://github.com/variety/variety) | 1122 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1121 | `npm run lint && npm run mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1120 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1116 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1113 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1110 | `nyc mocha --timeout=20000 test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1102 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1100 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1098 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1093 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1092 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1091 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1080 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1077 | `mocha tests/test-*` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1072 | `mocha --check-leaks --reporter spec --bail test/` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1071 | `mocha test/*` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1069 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1068 | `mocha $(find test -name '*.test.js')` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1068 | `mocha --compilers js:babel-register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1065 | `xo && mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1058 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1056 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1052 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1042 | `mocha --reporter spec --timeout 3000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1037 | `NODE_PATH=. mocha **/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1037 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1035 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1030 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1029 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1022 | `npm run prepublishOnly && mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1022 | `mocha` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1021 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1013 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1013 | `mocha test/tests.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1005 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1002 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1001 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1000 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 996 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 994 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 991 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 990 | `standard && mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 985 | `mocha --compilers js:babel-core/register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 985 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 983 | `mocha --recursive test` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 983 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 981 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 980 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [router5/router5](https://github.com/router5/router5) | 978 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 977 | `mocha -R spec ./test/unit/**` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 976 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 974 | `mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 973 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 969 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 964 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 963 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 962 | `mocha -R list` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 961 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 961 | `mocha tests/*.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 960 | `mocha -t 120000 test/*.test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 959 | `mocha ./test/test*.js --reporter spec` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 959 | `webpack && mocha test/unit` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 957 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 955 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [electron/asar](https://github.com/electron/asar) | 952 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 950 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 944 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 944 | `mocha --reporter spec` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 944 | `standard && mocha -b` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 941 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 938 | `nyc mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 934 | `mocha && standard` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 930 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 928 | `npm run lint && npm run mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 924 | `eslint src test && mocha --compilers babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 921 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 921 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 919 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 912 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 910 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 898 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 897 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 897 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 897 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 895 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 891 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 889 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 886 | `npm run lint && mocha --require @babel/register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 882 | `mocha --compilers js:babel-register test/*.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 879 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 878 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 877 | `mocha ./test -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 875 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 873 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 871 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 871 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 871 | `npm run convertto:es5 && npm run mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 869 | `mocha --reporter list` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 868 | `TEST=all mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 859 | `npm run lint && mocha -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 858 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 853 | `node_modules/.bin/mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 852 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 851 | `mocha tests` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 844 | `mocha -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 844 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 843 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 841 | `mocha` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 840 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 840 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 838 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 838 | `eslint test && mocha --compilers js:babel/register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 834 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 833 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 833 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 831 | `mocha --timeout 20000` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 829 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 822 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 820 | `mocha && ember test` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 819 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 817 | `mocha --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 816 | `mocha -t 600000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 816 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 813 | `mocha --check-leaks -t 20000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 812 | `standard && standard ./bin/* && mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 808 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 807 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 805 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 805 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 801 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 800 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 800 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 799 | `mocha test --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 799 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 798 | `mocha --require babel-register` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 797 | `npm run mocha:istanbul` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 795 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 792 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 792 | `nyc mocha specs` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 789 | `cake build && mocha ./test/mocha/*.coffee` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 787 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 786 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 785 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 783 | `mocha spec/*.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 782 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 779 | `./node_modules/.bin/mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 777 | `mocha --reporter list` | 
| [edsu/anon](https://github.com/edsu/anon) | 777 | `mocha --colors --reporter spec test.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 776 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 771 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 769 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 768 | `mocha --async-only` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 767 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 767 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 766 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 765 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 757 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 756 | `mocha --ui tdd --require ./test/__setup` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 755 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 748 | `mocha -R spec src/**/*_test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 745 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 743 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 739 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 736 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 735 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 734 | `mocha --recursive -s 15 test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 731 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 729 | `npm run mocha-test test/integration` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 728 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 727 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 722 | `mocha test.js` | 
| [developit/decko](https://github.com/developit/decko) | 714 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 714 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 713 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 713 | `mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 713 | `npm run build && istanbul test _mocha test/test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 712 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 712 | `mocha` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 712 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 712 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 709 | `mocha test --compilers js:babel-core/register` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 708 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 708 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 707 | `mocha tests/*.mocha.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 707 | `mocha test` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 705 | `npm run bundle && mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 705 | `mocha --harmony --full-trace --check-leaks` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 705 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 704 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 703 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 703 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 702 | `mocha test` | 