# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:59 05/02/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41145 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40356 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38079 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29343 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23870 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23029 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21908 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21871 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18589 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18158 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16085 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15571 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14031 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14014 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13221 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12556 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12343 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12132 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12114 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11946 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11898 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11439 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10961 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10702 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10266 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10141 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9750 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9596 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9595 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9515 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9479 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9080 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8758 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8667 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8651 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8415 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8273 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8260 | `mocha --check-leaks -R dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8199 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8179 | `grunt clean:test && mocha --exit` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8143 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8083 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 7970 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7949 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7889 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7769 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7687 | `npm run eslint && npm run mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7495 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7478 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7435 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7398 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7373 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7294 | `npm run build && istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7282 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6919 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6886 | `nyc mocha test/**/* -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6814 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6728 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6720 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6714 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6695 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6693 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6569 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6394 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6183 | `npm run lint -s && npm run mocha -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6048 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6026 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6015 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6012 | `npm run jshint && mocha test/` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5764 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5733 | `mocha test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5728 | `npm run build-cli && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5672 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5657 | `mocha tests/node.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5603 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5549 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5530 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5404 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5402 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5242 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5237 | `mocha --timeout 10000 && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5221 | `mocha; jshint *.js lib` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5159 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5078 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4990 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4866 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4864 | `gulp lint && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4821 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4804 | `standard && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4787 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4694 | `mocha test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4687 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4672 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4654 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4595 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4547 | `mocha ./test/runner.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4546 | `mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4531 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4446 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4444 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4408 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4382 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4315 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4307 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4290 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4126 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4087 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4069 | `nyc mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4011 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3998 | `npm run lint && npm run mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3965 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3955 | `mocha --require test/babel-hook test/*.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3927 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3925 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3888 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3863 | `export TESTING=true; mocha --reporter list` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3859 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3852 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3852 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3807 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3781 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3719 | `mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3696 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3677 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3676 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3676 | `npm run lint && npm run mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3658 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3610 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [primus/primus](https://github.com/primus/primus) | 3554 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3554 | `mocha tests/javascript` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3490 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3483 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3478 | `mocha --check-leaks --reporter spec --bail` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3455 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3443 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3423 | `node_modules/.bin/mocha test/lib/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3423 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3412 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3346 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3338 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3328 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3327 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3293 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3284 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3282 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3203 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3183 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3104 | `node_modules/.bin/mocha test/tests.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3103 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3100 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3098 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3075 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3065 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3062 | `NODE_ENV=test mocha test/**/*.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3048 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3008 | `nyc mocha && tsc` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2996 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2971 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2966 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2948 | `mocha test/*.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2939 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2931 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2929 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2916 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2866 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2859 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2841 | `NODE_ENV=test mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2841 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2839 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2828 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2816 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2809 | `mocha -R spec --recursive src/test` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2803 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2802 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2794 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2793 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2782 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2776 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2762 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2741 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2740 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2719 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2709 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2678 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2665 | `xo && mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2663 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2649 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2647 | `npm run mocha && npm run lint` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2645 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2642 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2642 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2637 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [css/csso](https://github.com/css/csso) | 2635 | `mocha --reporter dot` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2625 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2619 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2612 | `mocha --require babel-register --recursive spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2610 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2594 | `mocha-phantomjs ./test/index.html` | 
| [json5/json5](https://github.com/json5/json5) | 2381 | `nyc --reporter=html --reporter=text mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2379 | `mocha -R landing test/index` | 
| [mde/ejs](https://github.com/mde/ejs) | 2374 | `mocha --require should --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2367 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2365 | `mocha test` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2361 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2343 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2340 | `mocha "test/**/*-test.js"` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2335 | `mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2288 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2287 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2283 | `mocha test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2282 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2279 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2269 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2427 | `npm run build && cd test && mocha . --reporter dot` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2423 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2407 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2381 | `nyc --reporter=html --reporter=text mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2379 | `mocha -R landing test/index` | 
| [mde/ejs](https://github.com/mde/ejs) | 2374 | `mocha --require should --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2367 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2365 | `mocha test` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2361 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2343 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2340 | `mocha "test/**/*-test.js"` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2338 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2335 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2294 | `mocha test/unit --require mochahook` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2097 | `cross-env BABEL_ENV=test mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2096 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2094 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2094 | `mocha && eslint .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2075 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2069 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2010 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2097 | `cross-env BABEL_ENV=test mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2096 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2094 | `mocha test && npm run lint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2087 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2075 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2069 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2010 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1983 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1983 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1967 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2010 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1983 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1983 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1967 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1951 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1944 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1934 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1923 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1921 | `eslint . && mocha -t 5000` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1916 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1914 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1911 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1907 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1906 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1900 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1885 | `mocha --reporter spec --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1881 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1873 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1863 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1858 | `mocha --compilers js:babel-core/register __tests__` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1857 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1849 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1844 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1841 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [share/sharedb](https://github.com/share/sharedb) | 1820 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1813 | `mocha && eslint *.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1813 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1806 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1805 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1796 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1790 | `nyc npm run _mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1773 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1770 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1762 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1754 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1751 | `mocha --reporter spec && npm run test-typescript` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1741 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1741 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1739 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1739 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1737 | `npm run mocha && npm run karma` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1734 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1699 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1694 | `npm run lint && npm run mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1687 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1683 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1682 | `./node_modules/.bin/mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1681 | `mocha && npm run lint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1678 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1672 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1642 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1623 | `mocha test/**/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1616 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1605 | `npm run lint && mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1599 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1593 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1582 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1576 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1565 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1624 | `mocha --expose-gc --slow 300` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1623 | `mocha test/**/*.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1618 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1618 | `mocha ./test/basic.js -t 5000` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1616 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1605 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1604 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1599 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1593 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1582 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1576 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1565 | `mocha spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1553 | `npm run lint && npm run mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1548 | `mocha --compilers js:babel-register` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1532 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1520 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1509 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1506 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1505 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1494 | `mocha --reporter spec` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1494 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1492 | `npm run test:lint && npm run test:mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1490 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1471 | `eslint --cache . && tsc && mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1463 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1459 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1451 | `mocha --check-leaks -R dot` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1448 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1446 | `mocha test/tests.js --timeout=10000` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1429 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1426 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1413 | `mocha test.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1410 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1402 | `mocha --check-leaks --reporter spec --bail` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1397 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1388 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1386 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1378 | `nyc npm run mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1388 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1386 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1378 | `nyc npm run mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1375 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1373 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1342 | `istanbul cover _mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1292 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1288 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1285 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1278 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1275 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1270 | `mocha spec/exec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1263 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1261 | `mocha test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1260 | `istanbul cover _mocha test -- --timeout 20000` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1254 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1252 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1251 | `mocha --recursive` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1241 | `mocha --opts test/opts/mocha.opts` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1233 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1233 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1229 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1225 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1224 | `mocha tests` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1221 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1220 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1213 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1211 | `mocha test/unit` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1210 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1206 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1204 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1198 | `mocha test/**/*Spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1198 | `standard && istanbul cover _mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1194 | `nyc mocha --timeout=20000 test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1194 | `eslint src && mocha && karma start --single-run` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1193 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1192 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1190 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1189 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1188 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1184 | `mocha --reporter dot` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1182 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1180 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1178 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1173 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1168 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1167 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1155 | `node_modules/.bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1153 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1150 | `mocha src/test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1148 | `mocha tests/test-*` | 
| [normalize/mz](https://github.com/normalize/mz) | 1148 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1145 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1142 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1138 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1132 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1128 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1127 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1124 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1124 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1115 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1115 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1107 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1102 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1102 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1098 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1094 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1085 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1083 | `mocha $(find test -name '*.test.js')` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1082 | `mocha test/*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1080 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1072 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1071 | `npm run prepublishOnly && mocha test/test.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1070 | `mocha --compilers js:babel-register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1069 | `mocha -R spec ./test/unit/**` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1068 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1066 | `NODE_PATH=. mocha **/*.spec.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1062 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1061 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1055 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1055 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1052 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1042 | `mocha --recursive test` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1035 | `npm run lint && npm run mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1032 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1032 | `mocha tests/*.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1030 | `mocha ./test/test*.js --reporter spec` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1028 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1027 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1027 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1026 | `mocha test/tests.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1019 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1019 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1019 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1010 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1006 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1004 | `mocha --recursive --bail --reporter spec test` | 
| [router5/router5](https://github.com/router5/router5) | 1004 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1003 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1003 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1000 | `standard && mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 997 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 995 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 989 | `webpack && mocha test/unit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 987 | `mocha $(find test -name '*.test.js')` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 987 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 983 | `TEST=all mocha` | 
| [electron/asar](https://github.com/electron/asar) | 983 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 910 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 909 | `mocha "client.test" --compilers js:babel-register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 907 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 898 | `npm run convertto:es5 && npm run mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 896 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 895 | `mocha --compilers js:babel-register test/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 894 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 892 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 889 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 889 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 882 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 881 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 928 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 927 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 926 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 919 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 910 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 909 | `mocha "client.test" --compilers js:babel-register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 907 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 928 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 927 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 926 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 919 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 910 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 909 | `mocha "client.test" --compilers js:babel-register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 907 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 907 | `mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 902 | `mocha ./test -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 898 | `npm run convertto:es5 && npm run mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 896 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 894 | `mocha --timeout 20000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 892 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 892 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 889 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 889 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 882 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 881 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 878 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 871 | `mocha -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 870 | `npm run mocha:istanbul` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 870 | `mocha --reporter list` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 863 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 862 | `mocha tests` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 861 | `node_modules/.bin/mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 860 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 853 | `npm run lint && npm run mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 847 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 837 | `mocha -t 600000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 836 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 825 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 822 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 822 | `istanbul cover _mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 821 | `mocha -t 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 826 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 825 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 825 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 824 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 822 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 822 | `istanbul cover _mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 822 | `standard && standard ./bin/* && mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 821 | `mocha -t 5000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 819 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 817 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 817 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 813 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 812 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 812 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 811 | `nyc mocha specs` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 810 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 810 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 808 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 806 | `mocha spec/*.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 805 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 804 | `./node_modules/.bin/mocha -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 799 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 798 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 797 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 792 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 790 | `mocha --reporter list` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 790 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 789 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 780 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 777 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 776 | `nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 767 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 767 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 765 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 761 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 759 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 759 | `mocha test --compilers js:babel-core/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 753 | `mocha -R spec src/**/*_test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 752 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 724 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 724 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 724 | `mocha` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 722 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 721 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 720 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 719 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 717 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 717 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 716 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 714 | `mocha tests/*.mocha.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 714 | `mocha test` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 711 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 711 | `mocha --recursive ./test/*_spec.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 708 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 737 | `mocha --recursive -s 15 test/` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 735 | `./node_modules/.bin/mocha --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 733 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 733 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 733 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 732 | `nyc --check-coverage mocha test/*.test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 732 | `npm run build && istanbul test _mocha test/test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 730 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 730 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 728 | `mocha --harmony --full-trace --check-leaks` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 724 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 724 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 724 | `mocha` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 722 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 721 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 720 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 719 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 717 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 717 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 716 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 714 | `mocha test` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 711 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 711 | `mocha --recursive ./test/*_spec.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 708 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 