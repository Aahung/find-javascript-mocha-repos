# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:52 05/27/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41709 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40592 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38484 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29535 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24031 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23279 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22528 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22218 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18866 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18345 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16257 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15817 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14288 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14112 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13413 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12699 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12443 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12267 | `./node_modules/.bin/mocha test/` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12142 | `mocha --reporter spec` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12140 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12057 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11744 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11098 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10924 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10468 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10335 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9922 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9685 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9685 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9645 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9610 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9146 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 8126 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8002 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7922 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7573 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7523 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7514 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7471 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7324 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7120 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7025 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6975 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6846 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6821 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6765 | `xo && mocha test/*.js --timeout 100000` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7732 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7672 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7573 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7523 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7514 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7471 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7324 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7120 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7025 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6975 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6846 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6831 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6821 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6765 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6758 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6667 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6539 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6259 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6116 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6108 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6092 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6026 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6011 | `npm run build-cli && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5833 | `mocha test node-test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5819 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5804 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5797 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5707 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5585 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5581 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5553 | `mocha; jshint *.js lib` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5499 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5352 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5273 | `mocha --timeout 10000 && npm run lint` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5265 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5207 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5156 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5156 | `mocha src/**/*Tests.js --harmony` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5028 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4915 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4913 | `standard && mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4893 | `gulp lint && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4848 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4814 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4717 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4691 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4672 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4646 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4640 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4575 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4574 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4552 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4487 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4463 | `mocha test` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4452 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4414 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4343 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4320 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4319 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4220 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4188 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4186 | `NODE_ENV=test mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4138 | `nyc mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4092 | `nyc mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 4080 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4066 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3968 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3914 | `nyc mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3893 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3891 | `mocha -R spec ./test` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3872 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3850 | `npm run lint ; mocha && mocha test/individual` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3810 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3771 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3764 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3764 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3762 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3693 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3661 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3617 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3580 | `npm run build && mocha test/*.test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3572 | `mocha --check-leaks --reporter spec --bail` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3558 | `mocha tests/javascript` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3531 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3497 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3476 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3459 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3428 | `node_modules/.bin/mocha test/lib/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3425 | `nyc mocha "test/**/*.test.js"` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3419 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3414 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3408 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3390 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3380 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3339 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3331 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3328 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3297 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3243 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3163 | `NODE_ENV=test mocha test/**/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3124 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3113 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3112 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3111 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3108 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3073 | `mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3068 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3061 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3025 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3011 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2965 | `NODE_ENV=test mocha --exit` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2948 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2921 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2911 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2883 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2869 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2860 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2848 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2840 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2840 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2834 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2833 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2799 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2788 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2763 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2756 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2750 | `mocha --opts mocha.opts` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2799 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2788 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2763 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2756 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2750 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2746 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2727 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2722 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2719 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2719 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2717 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2703 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2689 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2686 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2679 | `xo && mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2669 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [css/csso](https://github.com/css/csso) | 2665 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2657 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2290 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2241 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2207 | `nyc --reporter=html --reporter=text mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2140 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2136 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2108 | `mocha -R spec test/*.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2491 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2477 | `npm run build && cd test && mocha . --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2462 | `mocha --require should --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2458 | `mocha --reporter=spec test/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2437 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2437 | `nyc --reporter=html --reporter=text mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2401 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2394 | `mocha "test/**/*-test.js"` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2385 | `mocha test/src/**/*.unit.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2378 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2373 | `mocha test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2367 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2364 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2352 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2340 | `mocha test/unit --require mochahook` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2340 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2334 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2316 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2290 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2285 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2282 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2255 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2241 | `mocha -R spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2236 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2207 | `nyc --reporter=html --reporter=text mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2108 | `mocha -R spec test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2083 | `eslint . && mocha -t 5000` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2083 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2078 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2042 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2031 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2007 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2001 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2042 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2031 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2007 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2001 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1969 | `mocha test/runner.js --reporter spec` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1966 | `mocha test/ --no-timeouts` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1956 | `mocha -c test/index.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1956 | `mocha -c test/index.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1953 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1948 | `mocha --require=test/test_helper.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1946 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1929 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1915 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1914 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1912 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1908 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1903 | `mocha --reporter spec --timeout 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1896 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1884 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1879 | `mocha --require ./test/common --growl test/expect.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1877 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1868 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1867 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1866 | `mocha tests.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1862 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1856 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1853 | `mocha && eslint *.js` | 
| [then/promise](https://github.com/then/promise) | 1849 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1844 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1840 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1834 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1821 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1799 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1796 | `mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1791 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1787 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1780 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1777 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1769 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1768 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1763 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1760 | `mocha -R spec spec spec/reporters` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1759 | `npm run mocha && npm run karma` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [pahen/madge](https://github.com/pahen/madge) | 1725 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1719 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1719 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1716 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1711 | `mocha && npm run lint` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1702 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1701 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1700 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1696 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1695 | `mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1692 | `mocha --reporter spec --grep .` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1691 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1691 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1687 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1686 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1659 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1649 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1645 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1637 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1633 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1632 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1628 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1626 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1614 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1610 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1609 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1604 | `mocha spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1593 | `mocha --compilers js:babel-register` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1589 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1584 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1560 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1550 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1538 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1530 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1524 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1500 | `npm run test:lint && npm run test:mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1492 | `eslint --cache . && tsc && mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1492 | `mocha compiled_tests/` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1482 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1478 | `node_modules/.bin/mocha --recursive` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1472 | `standard "./src/*.js" && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1471 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1471 | `mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1468 | `mocha tests.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1461 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1460 | `nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1457 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1456 | `mocha test/**/*.spec.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1455 | `mocha test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1453 | `mocha test/setup.js test/spec/*.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1472 | `standard "./src/*.js" && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1471 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1471 | `mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1468 | `mocha tests.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1461 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1460 | `nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1457 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1456 | `mocha test/**/*.spec.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1455 | `mocha test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1453 | `mocha test/setup.js test/spec/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1450 | `mocha test/tests.js --timeout=10000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1442 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1438 | `mocha --check-leaks --reporter spec --bail` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1433 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1431 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1430 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1395 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1368 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1353 | `mocha --timeout 10000 ./tests/lib.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1351 | `istanbul cover _mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1350 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1275 | `mocha spec/exec.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1274 | `nyc mocha --timeout=20000 test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1274 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1271 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1262 | `mocha --opts test/opts/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1256 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1246 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1245 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1241 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1240 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1239 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1236 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1235 | `eslint src && mocha && karma start --single-run` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1227 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1221 | `standard && istanbul cover _mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1221 | `standard && istanbul cover _mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1220 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1220 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1220 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1219 | `mocha --reporter dot` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1215 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1215 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1214 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1210 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1204 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1194 | `mocha tests/test-*` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1191 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1188 | `node ./node_modules/mocha/bin/mocha tests` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1187 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1185 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1183 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1183 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1183 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1183 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1174 | `mocha src/test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1174 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1174 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1169 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1166 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1164 | `mocha --reporter spec` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1157 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1157 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1151 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1148 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1143 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1134 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1133 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1132 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1130 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1130 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1121 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1116 | `mocha -R spec ./test/unit/**` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1107 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1102 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1101 | `npm run prepublishOnly && mocha test/test.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1099 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1099 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1096 | `NODE_ENV=test mocha tests/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1094 | `mocha $(find test -name '*.test.js')` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1092 | `mocha --recursive test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1091 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1091 | `mocha ./test/test*.js --reporter spec` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1090 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1087 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1086 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1085 | `mocha test/*` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1083 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1080 | `mocha --check-leaks -t 20000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1079 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1073 | `istanbul cover _mocha test/*.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1073 | `npm run lint && npm run mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1071 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1046 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1045 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1045 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1041 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1040 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1040 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1035 | `webpack && npm run lint && npm run mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1033 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1030 | `mocha test/tests.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1028 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1028 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1023 | `standard && mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1023 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1020 | `mocha --recursive --bail --reporter spec test` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1018 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1018 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1010 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1007 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1006 | `webpack && mocha test/unit` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1002 | `mocha --recursive test/bin` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1001 | `mocha $(find test -name '*.test.js')` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 999 | `mocha -t 120000 test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 997 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 996 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 989 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 987 | `mocha --recursive test/unit/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 985 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 983 | `standard && mocha -b` | 
| [tomas/needle](https://github.com/tomas/needle) | 981 | `mocha test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 981 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 989 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 987 | `mocha --recursive test/unit/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 985 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 983 | `standard && mocha -b` | 
| [tomas/needle](https://github.com/tomas/needle) | 981 | `mocha test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 981 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 981 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 974 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 974 | `mocha && standard` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 973 | `npm run lint && mocha --require @babel/register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 960 | `eslint src test && mocha --compilers babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 960 | `eslint src test && mocha --compilers babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 958 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 957 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 949 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 949 | `mocha --timeout 20000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 948 | `mocha --timeout 5000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 944 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 944 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 941 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 938 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 938 | `npm run mocha:istanbul` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 921 | `mocha "client.test" --compilers js:babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 920 | `npm run convertto:es5 && npm run mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 917 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 914 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 857 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 856 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 852 | `mocha -t 600000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 850 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 850 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 843 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 835 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 834 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 833 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 831 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 830 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 830 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 828 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 827 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 826 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 824 | `mocha spec/*.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 823 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 823 | `mocha test --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 819 | `./node_modules/.bin/mocha -R spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 817 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 817 | `istanbul cover -- _mocha --reporter spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 815 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 804 | `mocha --reporter spec --bail --check-leaks test/` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 800 | `mocha --reporter list` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 800 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 800 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 797 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 797 | `mocha test --compilers js:babel-core/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 795 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 785 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 784 | `./node_modules/.bin/mocha --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 784 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 782 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 777 | `npm run lint && mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 775 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 775 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 774 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 771 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 762 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 761 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 759 | `mocha --timeout 30000 --recursive ./tests` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 755 | `nyc --check-coverage mocha test/*.test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 753 | `mocha --harmony --full-trace --check-leaks` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 752 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 751 | `mocha test` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 749 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 749 | `mocha --recursive ./test/*_spec.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 747 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 745 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 744 | `mocha --recursive -s 15 test/` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 744 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 744 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 742 | `mocha test/index.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 740 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 737 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 716 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 712 | `npm run lint && npm run mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 710 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 706 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 705 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 698 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 720 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 720 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 716 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 712 | `npm run lint && npm run mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 710 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 710 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 706 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 705 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 705 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 706 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 705 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 705 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 702 | `mocha -r should --reporter spec test/*.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 698 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 697 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 696 | `mocha ./test/index.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 696 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 687 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 687 | `./bin/selenium-standalone install && mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 687 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 687 | `babel-node node_modules/.bin/_mocha -- test` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 687 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 685 | `mocha --reporter spec` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 683 | `mocha --reporter spec build/test/index.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 682 | `mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 680 | `mocha ./test/test.js --timeout 1000000` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 679 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 679 | `mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 678 | `nyc npm run mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 678 | `npm run-script jshint && npm run-script mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 678 | `nyc npm run mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 678 | `npm run-script jshint && npm run-script mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 672 | `mocha -b -R spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 672 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 672 | `./node_modules/.bin/mocha test/**/*` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 666 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 664 | `mocha $(find test -name '*.test.js')` | 