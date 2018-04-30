# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:53 04/30/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41100 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 40377 | `npm run mocha` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40342 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38006 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29332 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23865 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23015 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21866 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21857 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18563 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18149 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16070 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15558 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14025 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13991 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13214 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12546 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12330 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12126 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12113 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11944 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11878 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11425 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10956 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10682 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10254 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10126 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9737 | `mocha test/index.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9596 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9589 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9511 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9467 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9078 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8898 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8755 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8662 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8643 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8405 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8273 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8261 | `mocha --check-leaks -R dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8189 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8176 | `grunt clean:test && mocha --exit` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8128 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8079 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 7966 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7947 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7883 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7753 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7684 | `npm run eslint && npm run mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7496 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7467 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7435 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7390 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7363 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7291 | `npm run build && istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7272 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6907 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6879 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6862 | `npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6802 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6720 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6712 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6699 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6694 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6690 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6565 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6377 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6175 | `npm run lint -s && npm run mocha -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6042 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6026 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6018 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6005 | `npm run jshint && mocha test/` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5761 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5724 | `mocha test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5710 | `npm run build-cli && mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5654 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5653 | `mocha test/test.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5590 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5550 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5526 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5402 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5400 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5243 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5235 | `mocha --timeout 10000 && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5202 | `mocha; jshint *.js lib` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5153 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5070 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4982 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4863 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4862 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4811 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4790 | `standard && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4783 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4692 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4674 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4655 | `mocha --reporter spec -t 8000` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4648 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4594 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4551 | `mocha ./test/runner.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4538 | `mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4527 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4443 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4443 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4408 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4375 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4315 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4306 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4289 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4119 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4086 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4069 | `nyc mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3990 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3990 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3954 | `mocha --require test/babel-hook test/*.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3950 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3929 | `mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3919 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3864 | `export TESTING=true; mocha --reporter list` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3856 | `nyc mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3850 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3845 | `mocha -R spec ./test` | 
| [erming/shout](https://github.com/erming/shout) | 3808 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3775 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3717 | `mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3682 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3675 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3666 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3662 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3659 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3608 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3553 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3551 | `npm run build && mocha test/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3486 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3483 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3474 | `mocha --check-leaks --reporter spec --bail` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3453 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3445 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3423 | `node_modules/.bin/mocha test/lib/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3423 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3414 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3414 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3341 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3331 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3327 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3322 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3287 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3276 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3273 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3195 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3177 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3101 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3099 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3067 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3061 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3054 | `NODE_ENV=test mocha test/**/*.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 2995 | `nyc mocha && tsc` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2993 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2962 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2962 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2933 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2920 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2917 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2862 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2856 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2927 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2920 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2917 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2862 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2856 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2840 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2839 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2833 | `NODE_ENV=test mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2824 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2818 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2808 | `mocha -R spec --recursive src/test` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2798 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2797 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2792 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2791 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2778 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2776 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2759 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2738 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2735 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2716 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2709 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2680 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2665 | `xo && mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2659 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2649 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2645 | `npm run mocha && npm run lint` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2643 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2642 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2639 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2636 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [css/csso](https://github.com/css/csso) | 2632 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2618 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2616 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2610 | `mocha --timeout 100000` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2609 | `mocha --require babel-register --recursive spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2595 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2566 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2536 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2521 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2509 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2492 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2475 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2455 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2450 | `mocha --reporter=spec test/*-test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2447 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2427 | `npm run build && cd test && mocha . --reporter dot` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2401 | `nyc mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2377 | `mocha -R landing test/index` | 
| [json5/json5](https://github.com/json5/json5) | 2376 | `nyc --reporter=html --reporter=text mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2370 | `mocha --require should --reporter spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2365 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2362 | `mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2359 | `mocha test` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2344 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2339 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2338 | `mocha --no-colors --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2336 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2336 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2291 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2287 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2282 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2280 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2279 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2271 | `mocha test.js` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2266 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2249 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2239 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2227 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2222 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2216 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2177 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2171 | `mocha --compilers js:babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2099 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2096 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2094 | `mocha && eslint .` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2089 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2088 | `mocha test && npm run lint` | 
| [noble/noble](https://github.com/noble/noble) | 2085 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2075 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2065 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2008 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1950 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1944 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1933 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1921 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1917 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1916 | `eslint . && mocha -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1915 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1911 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1908 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1904 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1898 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1877 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1872 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1864 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1857 | `mocha --compilers js:babel-core/register __tests__` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1854 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1847 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1845 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1838 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [then/promise](https://github.com/then/promise) | 1830 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1819 | `./node_modules/.bin/mocha && npm run jshint` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1812 | `mocha && eslint *.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1806 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kach/nearley](https://github.com/kach/nearley) | 1805 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1804 | `npm run lint && mocha -R dot && npm run cover` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1798 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1766 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1758 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1753 | `npm run lint && mocha --reporter spec test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1749 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1741 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1739 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1739 | `mocha test` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1736 | `npm run mocha && npm run karma` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1729 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1715 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1699 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1687 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1683 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1682 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1715 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1699 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 1691 | `npm run lint && npm run mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1687 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1683 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1682 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1679 | `mocha && npm run lint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1677 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1667 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1665 | `mocha --reporter spec --grep .` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1657 | `standard "src/*.js" && npm run build && mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1653 | `mocha tests --compilers js:babel-core/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1650 | `mocha --reporter spec test/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1641 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1626 | `mocha test -u bdd -R spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 1626 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1624 | `mocha --expose-gc --slow 300` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1623 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1622 | `mocha test/**/*.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1617 | `mocha test/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1617 | `mocha tests/test.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1614 | `mocha ./test/basic.js -t 5000` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1605 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1604 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1604 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1602 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1592 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1585 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1519 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1509 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1506 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1504 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1494 | `npm run test:lint && npm run test:mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1488 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1519 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1509 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1506 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1504 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1494 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1493 | `mocha --reporter spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1488 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1470 | `eslint --cache . && tsc && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1464 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1458 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1449 | `mocha --check-leaks -R dot` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1448 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1439 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [zeit/ms](https://github.com/zeit/ms) | 1438 | `mocha tests.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1437 | `nyc mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1437 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1436 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1429 | `mocha compiled_tests/` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1428 | `standard "./src/*.js" && mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1428 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1426 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1385 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1384 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1377 | `nyc npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1373 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1372 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1361 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1342 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1340 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1342 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1340 | `istanbul cover _mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1331 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1329 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1329 | `mocha --timeout 10000 ./tests/lib.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1312 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1292 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1292 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1291 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1286 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1284 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1278 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1274 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1271 | `mocha spec/exec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1261 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1260 | `istanbul cover _mocha test -- --timeout 20000` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1257 | `mocha test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1253 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1249 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1249 | `mocha --recursive` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1241 | `mocha --opts test/opts/mocha.opts` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1234 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1234 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1230 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1223 | `mocha tests` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1221 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1220 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1217 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1211 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1210 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1209 | `mocha test/unit` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1206 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1204 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1199 | `mocha test/**/*Spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1195 | `standard && istanbul cover _mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1194 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1194 | `eslint src && mocha && karma start --single-run` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1192 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1190 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1190 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1188 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1188 | `nyc mocha --timeout=20000 test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1185 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1183 | `mocha --reporter dot` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1182 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1180 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1179 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1172 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1170 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1168 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1154 | `node_modules/.bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1152 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1150 | `mocha src/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1148 | `mocha --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1145 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1145 | `mocha tests/test-*` | 
| [variety/variety](https://github.com/variety/variety) | 1145 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1142 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1137 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1131 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1057 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1054 | `istanbul cover _mocha test/*.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1051 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1041 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1039 | `mocha --recursive test` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1030 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1030 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1029 | `npm run lint && npm run mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1026 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1026 | `mocha test/tests.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1025 | `mocha ./test/test*.js --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1023 | `mocha --compilers js:babel-core/register` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1020 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1020 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1016 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1006 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1006 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1084 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1081 | `mocha $(find test -name '*.test.js')` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1077 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1072 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1071 | `mocha --compilers js:babel-register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1068 | `npm run prepublishOnly && mocha test/test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1065 | `NODE_PATH=. mocha **/*.spec.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1064 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1062 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1062 | `mocha -R spec ./test/unit/**` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1057 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1054 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1051 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1051 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1041 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1039 | `mocha --recursive test` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1035 | `mocha --ui qunit --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1033 | `mocha tests/*.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1030 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1030 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1029 | `npm run lint && npm run mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1026 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1026 | `mocha test/tests.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1025 | `mocha ./test/test*.js --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1023 | `mocha --compilers js:babel-core/register` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 977 | `mocha -t 120000 test/*.test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 974 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 973 | `mocha test` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 967 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 965 | `mocha --async-only` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 963 | `standard && mocha -b` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 963 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 962 | `mocha --reporter spec --bail --check-leaks test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 957 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 956 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 953 | `mocha && standard` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 952 | `mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 947 | `mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 987 | `mocha $(find test -name '*.test.js')` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 987 | `webpack && mocha test/unit` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 984 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [electron/asar](https://github.com/electron/asar) | 983 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 981 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 978 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 977 | `TEST=all mocha` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 977 | `mocha -t 120000 test/*.test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 974 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 973 | `mocha test` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 967 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 965 | `mocha --async-only` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 964 | `mocha -R list` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 963 | `standard && mocha -b` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 963 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 962 | `mocha --reporter spec --bail --check-leaks test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 957 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 956 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 953 | `mocha && standard` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 952 | `mocha --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 950 | `eslint src test && mocha --compilers babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 947 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 942 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 941 | `npm run lint && mocha --require @babel/register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 928 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 927 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 926 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 918 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 910 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 909 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 907 | `mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 903 | `mocha ./test -R spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 901 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 897 | `npm run convertto:es5 && npm run mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 896 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 895 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 891 | `mocha --reporter spec --bail --check-leaks test/` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 890 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 889 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 889 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 888 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 885 | `npm-run-all test:jest test:mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 882 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 881 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 869 | `npm run mocha:istanbul` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 869 | `mocha -R spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 864 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 859 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 853 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 850 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 848 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 848 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 853 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 850 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 848 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 848 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 846 | `node_modules/.bin/mocha test/spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 846 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 844 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 837 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 835 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 835 | `mocha -t 600000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 826 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 825 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 825 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 823 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 822 | `mocha --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 822 | `standard && standard ./bin/* && mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 822 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 820 | `mocha -t 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 818 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 818 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 816 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 811 | `mocha test --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 811 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 809 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 808 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 806 | `mocha spec/*.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 805 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 804 | `./node_modules/.bin/mocha -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 800 | `mocha --require babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 798 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 796 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 792 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 792 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 789 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 788 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 787 | `mocha --reporter list` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 779 | `mocha --async-only` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 777 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 775 | `nyc mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 772 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 770 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 769 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 767 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 764 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 760 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 759 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 757 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 755 | `mocha test --compilers js:babel-core/register` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 751 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 747 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 745 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 745 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 740 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 739 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 738 | `mocha --recursive -s 15 test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 733 | `./node_modules/.bin/mocha --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 733 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 732 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 731 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 731 | `nyc --check-coverage mocha test/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 731 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 730 | `npm run build && istanbul test _mocha test/test.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 729 | `mocha --harmony --full-trace --check-leaks` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 728 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 728 | `mocha test` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 728 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 727 | `mocha test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 723 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 722 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 722 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 721 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 720 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 717 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 716 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 716 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 715 | `mocha` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 714 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 713 | `mocha tests/*.mocha.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 