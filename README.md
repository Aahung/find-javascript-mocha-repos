# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:03 04/19/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40813 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40254 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 40037 | `npm run mocha` | 
| [expressjs/express](https://github.com/expressjs/express) | 37748 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29238 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23795 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22885 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21689 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21510 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18443 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18055 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15985 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15469 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13990 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13841 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13130 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12501 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12295 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12094 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12054 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11899 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11757 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11277 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10886 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10589 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10161 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10041 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9663 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9554 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9554 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9448 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9422 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9051 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8806 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8718 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8609 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8546 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8306 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8261 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8247 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8158 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8135 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8052 | `./node_modules/.bin/mocha test/src` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8052 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7912 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7905 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7864 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7667 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7661 | `npm run eslint && npm run mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7485 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7434 | `mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7372 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7351 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7273 | `npm run build && istanbul cover _mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7270 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7157 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6820 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6812 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6744 | `npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6714 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6673 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6666 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6661 | `mocha $HARMONY_OPTS` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6659 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6652 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6516 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6292 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6160 | `npm run lint -s && npm run mocha -s` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6014 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6014 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6012 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5937 | `npm run jshint && mocha test/` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5735 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5675 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5623 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5592 | `mocha test/test.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5569 | `npm run build-cli && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5529 | `mocha && eslint lib/**` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5523 | `mocha --exit --require babel-core/register` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5498 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5352 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5219 | `mocha --timeout 10000 && npm run lint` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5201 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5162 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5150 | `mocha src/**/*Tests.js --harmony` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5021 | `mocha; jshint *.js lib` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5012 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4864 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4849 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4838 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4800 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4773 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4745 | `standard && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4724 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [santinic/how2](https://github.com/santinic/how2) | 4687 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4664 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4653 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4582 | `gulp build; mocha;` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4580 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4545 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4510 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4504 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4429 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4405 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4389 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4350 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4296 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4271 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4094 | `mocha --recursive && make test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4056 | `nyc mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4043 | `NODE_ENV=test mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3954 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3953 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3940 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3920 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3890 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3866 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3861 | `export TESTING=true; mocha --reporter list` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3851 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3839 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3815 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3801 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3801 | `mocha -R spec ./test` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3747 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3694 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3665 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3655 | `npm run jshint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3651 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3613 | `npm run lint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3602 | `standard && mocha --timeout 60000 test/test.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3599 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3556 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3554 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3538 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3484 | `mocha --reporter spec --timeout 3000` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3463 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3447 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3439 | `node_modules/.bin/mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3438 | `mocha --check-leaks --reporter spec --bail` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3423 | `node_modules/.bin/mocha test/lib/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3412 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3411 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3316 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3310 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3307 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3284 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3256 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3224 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3203 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3149 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3145 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3103 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3099 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3098 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3086 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3050 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3034 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3003 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3003 | `NODE_ENV=test mocha test/**/*.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2987 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2960 | `nyc mocha && tsc` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2956 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2940 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2933 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2910 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2892 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2881 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2876 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2871 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2846 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2833 | `mocha test/index.js && npm run demo` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2818 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2818 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2811 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2811 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2808 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2786 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2775 | `NODE_ENV=test mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2774 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2769 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2767 | `mocha --require should --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2766 | `istanbul cover _mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2766 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2753 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2742 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2728 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2726 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2721 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2701 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2691 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2688 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2661 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2659 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2638 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2634 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [css/csso](https://github.com/css/csso) | 2626 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2623 | `npm run mocha && npm run lint` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2620 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2615 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2606 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2605 | `mocha --timeout 100000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2604 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2600 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2595 | `mocha-phantomjs ./test/index.html` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2593 | `mocha --compilers js:babel-register --recursive spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2592 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2553 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2530 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2524 | `export TESTING=true; mocha --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2508 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2484 | `node_modules/.bin/mocha --reporter spec` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2475 | `export TESTING=true; mocha --reporter list` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2468 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2451 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2444 | `mocha --reporter=spec test/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2438 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2429 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2421 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2405 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2392 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2362 | `mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2362 | `nyc --reporter=html --reporter=text mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2356 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2351 | `mocha test` | 
| [mde/ejs](https://github.com/mde/ejs) | 2345 | `mocha --require should --reporter spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2339 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2335 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2335 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2321 | `mocha -R landing test/index` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2318 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2304 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2281 | `mocha test/unit --require mochahook` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2280 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2279 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2266 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2256 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2240 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2236 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2235 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2226 | `mocha test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2222 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2213 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2166 | `mocha --compilers js:babel-register` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2153 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2087 | `cross-env BABEL_ENV=test mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2081 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2079 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2071 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2070 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2063 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2054 | `mocha test && npm run lint` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2053 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1998 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1970 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1961 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1947 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1945 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1941 | `mocha --require=test/test_helper.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1911 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1910 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1910 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1908 | `mocha --bail --reporter spec --check-leaks test/` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1906 | `mocha test/runner.js --reporter spec` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1903 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1881 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1875 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1871 | `mocha --reporter spec --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1869 | `mocha --require ./test/common --growl test/expect.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1866 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1860 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1839 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1836 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1824 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1824 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [then/promise](https://github.com/then/promise) | 1821 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1811 | `eslint . && mocha -t 5000` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1805 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1802 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1798 | `mocha && eslint *.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1796 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [kach/nearley](https://github.com/kach/nearley) | 1796 | `mocha test/*.test.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1793 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1788 | `npm run lint && mocha -R dot && npm run cover` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1777 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1770 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1769 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1767 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1759 | `nyc npm run _mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1756 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1751 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1748 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1742 | `mocha --reporter spec && npm run test-typescript` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1733 | `mocha test` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1731 | `mocha -R spec spec spec/reporters` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1731 | `npm run mocha && npm run karma` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1729 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1710 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1708 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1697 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1681 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1678 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1678 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1677 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1672 | `npm run lint && npm run mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1668 | `mocha && npm run lint` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1663 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1653 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1650 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1644 | `mocha tests --compilers js:babel-core/register` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1626 | `standard "src/*.js" && npm run build && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1623 | `mocha --expose-gc --slow 300` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1622 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1618 | `mocha test -u bdd -R spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1616 | `mocha --reporter spec test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1613 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1612 | `mocha test/*.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1611 | `mocha test/**/*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1600 | `mocha ./test/basic.js -t 5000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1600 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1594 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1587 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1586 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1581 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1572 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1559 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1541 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1527 | `mocha --compilers js:babel-register` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1527 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1517 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1510 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1506 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1505 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1503 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1492 | `npm run test:lint && npm run test:mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1491 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1486 | `mocha --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1473 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1464 | `node_modules/.bin/mocha --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1453 | `eslint --cache . && tsc && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1452 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1446 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1446 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1445 | `mocha test/tests.js --timeout=10000` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1436 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1432 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1431 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1425 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1422 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1420 | `standard "./src/*.js" && mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1420 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1414 | `mocha test.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1414 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1412 | `mocha compiled_tests/` | 
| [zeit/ms](https://github.com/zeit/ms) | 1411 | `mocha tests.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1399 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1392 | `mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1388 | `mocha --check-leaks --reporter spec --bail` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1385 | `mocha test/setup.js test/spec/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1382 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1373 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1371 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1361 | `nyc npm run mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1360 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1338 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1335 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1324 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1323 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1318 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1310 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1285 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1285 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1280 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1279 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1274 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1270 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1263 | `mocha spec/exec.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1254 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1253 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1244 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1243 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1239 | `mocha --recursive` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1233 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1232 | `mocha test/*.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1229 | `mocha --opts test/opts/mocha.opts` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1223 | `mocha test` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1222 | `mocha tests` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1222 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1211 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1209 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1207 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1204 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1203 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1201 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1200 | `mocha test/unit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1195 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1193 | `mocha test/**/*Spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1188 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1188 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1188 | `eslint src && mocha && karma start --single-run` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1186 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1186 | `standard && istanbul cover _mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1182 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1182 | `node ./node_modules/mocha/bin/mocha tests` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1181 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1181 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1180 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1178 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1177 | `mocha test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1176 | `mocha --reporter dot` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1175 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1168 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1166 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1160 | `nyc mocha --timeout=20000 test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1148 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1147 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1146 | `node_modules/.bin/mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1141 | `mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1139 | `mocha src/test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1139 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1136 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1135 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1131 | `mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1125 | `mocha tests/test-*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1124 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1123 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1121 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1119 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1102 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1102 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1100 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1100 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1097 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1093 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1082 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1081 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1079 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1078 | `xo && mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1070 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1067 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1064 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1056 | `npm run prepublishOnly && mocha test/test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1050 | `NODE_PATH=. mocha **/*.spec.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1049 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1047 | `istanbul cover _mocha test/*.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1046 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1041 | `mocha -R spec ./test/unit/**` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1040 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1037 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1033 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1026 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1023 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1022 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1022 | `mocha --recursive test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1021 | `mocha test/tests.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1013 | `npm run lint && npm run mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1010 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1010 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1010 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1009 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1008 | `mocha --compilers js:babel-core/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1007 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1004 | `mocha tests/*.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1000 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1000 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 999 | `mocha ./test/test*.js --reporter spec` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 997 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 997 | `standard && mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [router5/router5](https://github.com/router5/router5) | 995 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 982 | `mocha $(find test -name '*.test.js')` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 980 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 978 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 974 | `webpack && mocha test/unit` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 972 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [electron/asar](https://github.com/electron/asar) | 972 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 971 | `mocha -t 120000 test/*.test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 970 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 969 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 966 | `webpack && npm run lint && npm run mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 964 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 962 | `mocha --async-only` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 962 | `mocha -R list` | 
| [tomas/needle](https://github.com/tomas/needle) | 962 | `mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 957 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 956 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 955 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 954 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 949 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [electron/spectron](https://github.com/electron/spectron) | 947 | `mocha && standard` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 947 | `mocha --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 944 | `TEST=all mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 942 | `eslint src test && mocha --compilers babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 940 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 932 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 928 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 925 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 921 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 917 | `npm run lint && mocha --require @babel/register` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 917 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 912 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 907 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 906 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 905 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 900 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 893 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 891 | `mocha ./test -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 887 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 887 | `mocha --compilers js:babel-register test/*.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 887 | `npm run convertto:es5 && npm run mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 886 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 884 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 881 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 880 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 877 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 877 | `npm-run-all test:jest test:mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 873 | `npm run lint && mocha -R spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 872 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 867 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 867 | `mocha --timeout 20000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 861 | `mocha -R spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 859 | `mocha tests` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 859 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 856 | `node_modules/.bin/mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 855 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 852 | `npm run mocha:istanbul` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 849 | `npm run lint && npm run mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 847 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 846 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 845 | `node_modules/.bin/mocha test/spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 845 | `mocha --timeout 200000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 844 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 834 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 833 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 826 | `mocha -t 600000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 824 | `mocha --check-leaks -t 20000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 822 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 822 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 821 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 820 | `mocha --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 818 | `standard && standard ./bin/* && mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 815 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 815 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 815 | `mocha -t 5000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 815 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 812 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 809 | `nyc mocha specs` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 808 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 808 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 805 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 802 | `mocha test --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 800 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 799 | `mocha --require babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 799 | `istanbul cover -- _mocha --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 797 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 796 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 793 | `./node_modules/.bin/mocha -R spec` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 792 | `mocha spec/*.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 788 | `cake build && mocha ./test/mocha/*.coffee` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 787 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 786 | `mocha --reporter list` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 786 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 783 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 779 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [edsu/anon](https://github.com/edsu/anon) | 778 | `mocha --colors --reporter spec test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 774 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 773 | `mocha --async-only` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 769 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 769 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 769 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 767 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 762 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 757 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 751 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 751 | `mocha -R spec src/**/*_test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 750 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 749 | `nyc mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 744 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 742 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 741 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 740 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 736 | `mocha --recursive -s 15 test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 733 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 731 | `mocha test --compilers js:babel-core/register` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 726 | `nyc --check-coverage mocha test/*.test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 726 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 726 | `mocha test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 725 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 725 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 723 | `npm run build && istanbul test _mocha test/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 723 | `./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 721 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 721 | `mocha test` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 720 | `mocha` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 720 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 718 | `mocha --harmony --full-trace --check-leaks` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 718 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 718 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 717 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 717 | `mocha test` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 715 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 714 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 714 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 713 | `mocha tests/*.mocha.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 713 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 