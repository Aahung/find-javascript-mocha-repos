# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:39 02/19/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45219 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42471 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42258 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30917 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26058 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25818 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25299 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25244 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21582 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20192 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18117 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18001 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17625 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15398 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15081 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14738 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14055 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13751 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13320 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13048 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12834 | `mocha --reporter spec test/*-test.js` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13751 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13320 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13048 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12834 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12828 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12598 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12566 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12367 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12364 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11656 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11354 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11253 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10957 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10708 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10621 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10455 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9899 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9825 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9733 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9596 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9497 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9457 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9358 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9137 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8967 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8906 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8816 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8712 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8618 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8594 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8484 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8431 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8314 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8276 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8245 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8080 | `npm run eslint && npm run mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8060 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8055 | `./node_modules/.bin/mocha test` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8006 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7979 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7907 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7615 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7603 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7584 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7576 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7547 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7327 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7221 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7132 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7089 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7034 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6949 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6066 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5902 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5848 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5829 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5803 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5725 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5668 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5625 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5596 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5457 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5433 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5378 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5378 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6030 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5925 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5902 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5848 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5829 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5803 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [teambit/bit](https://github.com/teambit/bit) | 5747 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5725 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5668 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5625 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5596 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5457 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5433 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5378 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5378 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5200 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5134 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5130 | `mocha --color` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5109 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5076 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5017 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4979 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4965 | `nyc mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4930 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4926 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4902 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4102 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4041 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4033 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3980 | `npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3970 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3944 | `NODE_ENV=test mocha test/**/*.js` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3918 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3835 | `mocha && tsc -p ./test/types` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3833 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3784 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3746 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3738 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3720 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3679 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3678 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3639 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3602 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3593 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3572 | `nyc mocha && tsc` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3517 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3514 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3499 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3449 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3441 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3426 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3411 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3401 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3398 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3358 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3350 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3320 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3270 | `mocha test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3251 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3248 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3231 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3212 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3270 | `mocha test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3251 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3249 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3248 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3231 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3212 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3178 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3176 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3172 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3123 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3105 | `nyc mocha --recursive` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3096 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3089 | `npm run mocha && npm run lint` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3073 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3073 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3065 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3048 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3037 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3020 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3018 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2998 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2990 | `mocha --require @babel/register --recursive spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2988 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2975 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2968 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2966 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2953 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2920 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2917 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2912 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2910 | `mocha -R spec spec spec/reporters` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1882 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1865 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1851 | `npm run lint && npm run mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1847 | `eslint --cache . && tsc && mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1808 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1795 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1791 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1775 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1753 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1749 | `mocha test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1741 | `./node_modules/.bin/mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1734 | `mocha --check-leaks --reporter spec --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1720 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1713 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2451 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2432 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2412 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2399 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2387 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2331 | `npm run lint && npm run mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2321 | `mocha --compilers js:babel-register` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2320 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2303 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2299 | `mocha test/**/*.coffee` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2299 | `mocha test/**/*.coffee` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2278 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2267 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2245 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2241 | `npm run lint && mocha tests/**/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2213 | `./node_modules/.bin/mocha && npm run jshint` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2211 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2202 | `mocha test/runner.js --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2190 | `cross-env BABEL_ENV=test mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2168 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2162 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2146 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2387 | `grunt jshint && mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2331 | `npm run lint && npm run mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2321 | `mocha --compilers js:babel-register` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2320 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2309 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2303 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2299 | `mocha test/**/*.coffee` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2278 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1964 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1961 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1955 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1928 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1925 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1903 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1898 | `mocha --recursive` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1892 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1882 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1865 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1851 | `npm run lint && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2213 | `./node_modules/.bin/mocha && npm run jshint` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2211 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2202 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2198 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2190 | `cross-env BABEL_ENV=test mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2172 | `mocha test/test-*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2168 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2162 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2154 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2146 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2143 | `mocha --compilers js:babel-core/register __tests__` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2130 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2091 | `mocha test/*.test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2068 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2053 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2052 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2049 | `mocha && npm run lint` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2027 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2016 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2014 | `mocha --require=test/test_helper.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1979 | `mocha --require ./test/common --growl test/expect.js` | 
| [then/promise](https://github.com/then/promise) | 2016 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2014 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2001 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1994 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1979 | `mocha --require ./test/common --growl test/expect.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1976 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1969 | `mocha --reporter spec && npm run test-typescript` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1964 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1961 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1955 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1808 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1795 | `mocha --timeout 5000` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1790 | `mocha ./test/test*.js --reporter spec` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1775 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1756 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1733 | `mocha test --timeout 600000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1728 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1726 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1720 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1713 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1823 | `mocha test/setup.js test/spec/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1808 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1795 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1791 | `mocha tests.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1790 | `mocha ./test/test*.js --reporter spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1784 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1775 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1771 | `npm run lint && mocha && npm run typescript` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1649 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1642 | `mocha tests/test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1636 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1631 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1622 | `mocha --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1618 | `mocha test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1608 | `mocha test/unit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1597 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1591 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1586 | `mocha tests/test-*` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1582 | `nyc mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1720 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1713 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1689 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1688 | `mocha && size-limit` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1685 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1671 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1665 | `mocha spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1664 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1663 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1662 | `NODE_ENV=test mocha tests/*.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1560 | `mocha --check-leaks --require @babel/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1550 | `node_modules/.bin/mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1549 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1543 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1535 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1532 | `npm run lint && mocha && karma start --single-run` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1530 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1528 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1525 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1513 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1512 | `mocha test/**/*.spec.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1507 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1504 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1515 | `mocha --timeout 10000 ./tests/lib.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1513 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1512 | `mocha test/**/*.spec.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1509 | `mocha -R spec test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1507 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1504 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1497 | `mocha --recursive test` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1496 | `standard && istanbul cover _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1494 | `npm run prepublishOnly && mocha test/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1483 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1482 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1480 | `mocha --reporter dot` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1480 | `mocha -R spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1478 | `mocha --opts test/opts/mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1543 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1537 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1535 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1532 | `npm run lint && mocha && karma start --single-run` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1530 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1528 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1525 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1515 | `mocha --timeout 10000 ./tests/lib.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1513 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1512 | `mocha test/**/*.spec.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1509 | `mocha -R spec test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1507 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1504 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1355 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1344 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1339 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1338 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1334 | `mocha tests/` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1331 | `mocha --timeout 60000 test/` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1327 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1327 | `mocha test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1326 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1326 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1326 | `mocha` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1325 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1322 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1319 | `mocha src/test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1315 | `mocha --timeout 30000 --recursive ./tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1312 | `mocha --timeout 20000` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1311 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1307 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1305 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1303 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1300 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1297 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1296 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1284 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1273 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1273 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1263 | `mocha tests` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1259 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1259 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1245 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1244 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [electron/asar](https://github.com/electron/asar) | 1239 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1230 | `node ./node_modules/mocha/bin/mocha tests` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1230 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1216 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1208 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1203 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1201 | `mocha --reporter spec --bail --check-leaks test/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1199 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1196 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1194 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1191 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1105 | `mocha --recursive --bail --reporter spec test` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1099 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1097 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1084 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1081 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1058 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [electron/spectron](https://github.com/electron/spectron) | 1144 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1134 | `standard && mocha -b` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1130 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1124 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1108 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1106 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1106 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1105 | `mocha --recursive --bail --reporter spec test` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1099 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1097 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1089 | `npm run lint && npm run mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1074 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1058 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1053 | `mocha $(find test -name '*.test.js')` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1048 | `mocha test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1048 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1046 | `mocha --recursive ./test/*_spec.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 989 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 977 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 976 | `mocha -t 600000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 976 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 975 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 971 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 970 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 968 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 918 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 916 | `mocha test/index.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 913 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 907 | `npm run lint && npm run mocha:no-functional` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 942 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 942 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 938 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 919 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 916 | `mocha test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 916 | `mocha spec/*.spec.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 916 | `mocha test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 916 | `mocha spec/*.spec.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 913 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 907 | `npm run lint && npm run mocha:no-functional` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 907 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 898 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 893 | `npm run build && istanbul test _mocha test/test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 887 | `mocha --harmony --full-trace --check-leaks` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 884 | `mocha --reporter list` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 877 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 872 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 872 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 866 | `npm run lint && mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 864 | `eslint test && mocha --compilers js:babel/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 860 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 858 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 854 | `mocha -r babel-register --check-leaks test/index.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 852 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 850 | `nyc mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 848 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 866 | `npm run lint && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 864 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 864 | `eslint test && mocha --compilers js:babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 863 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 862 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 858 | `mocha --reporter spec --bail --check-leaks test/` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 858 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 856 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 854 | `mocha -r babel-register --check-leaks test/index.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 854 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 852 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 852 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 850 | `nyc mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 848 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 845 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 841 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 840 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 840 | `mocha test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 838 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 834 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 834 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 832 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 831 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 810 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 808 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 808 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 805 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 801 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 794 | `jenkins-mocha ./tests/*.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 815 | `_mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 815 | `mocha test/mocha.js test/crc/index.js` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 813 | `mocha test` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 811 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 810 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 808 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 808 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 807 | `mocha test` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 801 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 801 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 796 | `eslint . && mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 795 | `npm run lint && npm run mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 794 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 793 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 790 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 736 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 734 | `mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 731 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 730 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 729 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 725 | `mocha --reporter spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [formio/formio](https://github.com/formio/formio) | 722 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 721 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 721 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 719 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 769 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 768 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 767 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 764 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 762 | `./bin/selenium-standalone install && mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 756 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 745 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 744 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [electron/apps](https://github.com/electron/apps) | 740 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 738 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 738 | `mocha --compilers js:babel-core/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 736 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 736 | `mocha ./test/test.js --timeout 1000000` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 735 | `mocha $(find test -name '*.test.js')` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 735 | `mocha --reporter spec --bail --check-leaks test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 734 | `mocha` | 