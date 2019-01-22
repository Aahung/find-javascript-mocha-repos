# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:22 01/22/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44956 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42019 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41996 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30840 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25566 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25160 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25000 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21339 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20085 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18423 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17973 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17798 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17208 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15187 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14898 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14682 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13921 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13632 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12996 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12984 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12763 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12747 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12417 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12359 | `mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12353 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12259 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11466 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11119 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11068 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10865 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10786 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9710 | `mocha tests/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9692 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9505 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9424 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9375 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9301 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8889 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8840 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8686 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8680 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8571 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8448 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8343 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8252 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8686 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8680 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8571 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8556 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8448 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8343 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8252 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8170 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8053 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8052 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8009 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7917 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7859 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7850 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7808 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7587 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7585 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7510 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7465 | `mocha; jshint *.js lib` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7456 | `mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7446 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7440 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7142 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7109 | `mocha $HARMONY_OPTS` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7089 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7003 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6827 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6827 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5881 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5742 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5693 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5686 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5685 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5614 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5533 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [teambit/bit](https://github.com/teambit/bit) | 5396 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5365 | `mocha -r esm` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5357 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5333 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5259 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5881 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5742 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5693 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5686 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5685 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5614 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5533 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5475 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [teambit/bit](https://github.com/teambit/bit) | 5396 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5365 | `mocha -r esm` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5357 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5333 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5259 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5156 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5120 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5037 | `mocha --recursive` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4998 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4946 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4919 | `nyc mocha --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4914 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4895 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4885 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4884 | `./node_modules/.bin/mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4857 | `npm run lint && npm run mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4855 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4840 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4829 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4804 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4746 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4609 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4583 | `mocha ./test/runner.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4563 | `mocha -R spec src` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4540 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4478 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4420 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4372 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4367 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4359 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4337 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4305 | `NODE_ENV=test mocha --exit` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4299 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4233 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4197 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4138 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4117 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4090 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4085 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4045 | `nyc mocha "test/**/*.test.js"` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4003 | `npm run build && cd test && mocha . --reporter dot` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4045 | `nyc mocha "test/**/*.test.js"` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4003 | `npm run build && cd test && mocha . --reporter dot` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3974 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3974 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3928 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3920 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3879 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3859 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3830 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3811 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3768 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3653 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3641 | `npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3593 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3582 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3527 | `nyc mocha && tsc` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3519 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3489 | `node_modules/.bin/mocha test/lib/` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3451 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3444 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3423 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3412 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3403 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3396 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3375 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3451 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3444 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3423 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3412 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3403 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3396 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3375 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3353 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3343 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3339 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3339 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3316 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3294 | `mocha test/index.js && npm run demo` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2710 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2686 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2659 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2591 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2585 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2550 | `mocha test` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2546 | `mocha test --exit && npm run lint` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2533 | `mocha test/src/**/*.unit.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2530 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2494 | `TEST=all mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2885 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2871 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2846 | `istanbul cover _mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2820 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2815 | `mocha --reporter dot` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2806 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2779 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2765 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2757 | `xo && mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2753 | `mocha "./test/**/*-test.js"` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2750 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2742 | `mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 2741 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2710 | `mocha --recursive --watch` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2221 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2219 | `npm run lint && mocha tests/**/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2199 | `mocha && eslint *.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2184 | `cross-env BABEL_ENV=test mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2180 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2175 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2172 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2159 | `./node_modules/.bin/mocha && npm run jshint` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2146 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2138 | `mocha --compilers js:babel-register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2130 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2126 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2088 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2205 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2184 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2184 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2180 | `mocha test/**/*.coffee` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2138 | `mocha --compilers js:babel-register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2138 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2088 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 2050 | `mocha test/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2276 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 2262 | `npm run lint && npm run mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2245 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2238 | `standard && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2221 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2219 | `npm run lint && mocha tests/**/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2199 | `mocha && eslint *.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2184 | `cross-env BABEL_ENV=test mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2180 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2175 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2172 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2159 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2156 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2088 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2038 | `npm run mocha && npm run karma` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2037 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2028 | `mocha tests --require @babel/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2019 | `mocha --reporter spec --timeout 5000` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2015 | `mocha && npm run lint` | 
| [then/promise](https://github.com/then/promise) | 2011 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1993 | `mocha test` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1982 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1967 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1961 | `mocha --bail --reporter spec --check-leaks test/` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1954 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1950 | `mocha --reporter spec && npm run test-typescript` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1948 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1947 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1945 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1928 | `npm run lint && mocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1926 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1911 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1900 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1895 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1882 | `mocha compiled_tests/` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1879 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1869 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1858 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1841 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1825 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [zeit/ms](https://github.com/zeit/ms) | 1760 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1757 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1747 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1742 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1737 | `mocha test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1736 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1725 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1723 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1715 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1714 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1712 | `mocha test/test-*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1706 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1706 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1704 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1521 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1507 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1503 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1496 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1495 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1470 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1463 | `standard && istanbul cover _mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1445 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1433 | `mocha test --compilers js:babel-core/register` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1408 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1407 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1695 | `mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1694 | `mocha --check-leaks --reporter spec --bail` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1684 | `mocha && size-limit` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1677 | `mocha ./test/test*.js --reporter spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1675 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1662 | `mocha spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1651 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1650 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1638 | `mocha tests/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1616 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1612 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1611 | `mocha test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1604 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1588 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1574 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1572 | `nyc mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1564 | `mocha -R spec ./test/unit/**` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1521 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1513 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1511 | `npm run lint && npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1507 | `mocha test/**/*.spec.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1503 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1498 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1496 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1495 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1491 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1468 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1461 | `mocha --reporter dot` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1459 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1491 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1470 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1468 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1463 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1461 | `mocha --reporter dot` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1459 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1453 | `mocha --opts test/opts/mocha.opts` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1452 | `npm run prepublishOnly && mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1452 | `mocha --recursive test` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1451 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1445 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1294 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1294 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1292 | `istanbul test _mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1291 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1288 | `mocha --timeout 20000` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1286 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1267 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1259 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1250 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1237 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1235 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1238 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1235 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1232 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1223 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1217 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1198 | `mocha --recursive -r tests/setup tests` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1183 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1179 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1178 | `mocha --reporter spec --bail --check-leaks test/` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1175 | `xo && mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1172 | `mocha --reporter spec --bail --check-leaks test/` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1168 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1167 | `mocha $(find test -name '*.test.js') --exit` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1167 | `npm-run-all test:jest test:server:mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1165 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1165 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1164 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1147 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1146 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1141 | `webpack && mocha test/unit` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1138 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1137 | `mocha --reporter spec test --recursive` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1129 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1125 | `npm run convertto:es5 && npm run mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1124 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1119 | `standard && mocha -b` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1117 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1114 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1088 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1099 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1097 | `mocha --recursive --bail --reporter spec test` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1096 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1088 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1080 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1080 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1066 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1064 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1062 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1053 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1029 | `mocha --reporter spec --timeout 3000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1023 | `mocha test/*.test.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1022 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1019 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1013 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1011 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1011 | `mocha --recursive ./test/*_spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1004 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 982 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 982 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 979 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 974 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 971 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 971 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 965 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 965 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 961 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 960 | `mocha tests` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 918 | `mocha -t 5000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 917 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 908 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 908 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 907 | `mocha test/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 904 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 903 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 896 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 908 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 907 | `mocha test/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 904 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 896 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 893 | `mocha --timeout 200000` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 887 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 884 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 883 | `npm run build && istanbul test _mocha test/test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 854 | `mocha --reporter spec --bail --check-leaks test/` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 853 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 847 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 846 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 845 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 845 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 845 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 838 | `mocha -r babel-register --check-leaks test/index.js` | 
| [developit/decko](https://github.com/developit/decko) | 837 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 837 | `mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 833 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 832 | `nyc mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 854 | `mocha --reporter spec --bail --check-leaks test/` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 853 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 849 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 848 | `mocha --opts mocha.opts` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 846 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 845 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 845 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [developit/decko](https://github.com/developit/decko) | 837 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 837 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 834 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 832 | `nyc mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 830 | `npm run lint && mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 829 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 829 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 827 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 825 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 822 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 819 | `npm run mocha-test test/integration` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 818 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 816 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 814 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 813 | `_mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 810 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 810 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 802 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 799 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 799 | `mocha test` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 798 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 797 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 796 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 786 | `nyc mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 784 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 782 | `mocha tests --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 781 | `mocha --recursive -s 15 test/` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 772 | `babel-node node_modules/.bin/_mocha -- test` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 772 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 770 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 774 | `mocha test` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 772 | `babel-node node_modules/.bin/_mocha -- test` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 770 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 770 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 768 | `eslint . && mocha` | 
| [koajs/static](https://github.com/koajs/static) | 766 | `mocha --harmony --reporter spec --exit` | 
| [susam/texme](https://github.com/susam/texme) | 766 | `standard && mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 764 | `npm run-script jshint && npm run-script mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 763 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 763 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 761 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 760 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 756 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 756 | `./bin/selenium-standalone install && mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 753 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 753 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 741 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 741 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 738 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 735 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 730 | `mocha $(find test -name '*.test.js')` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 729 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 738 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 730 | `mocha $(find test -name '*.test.js')` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 729 | `mocha ./test/test.js --timeout 1000000` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 729 | `mocha --reporter spec --bail --check-leaks test/` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 728 | `mocha --compilers js:babel-core/register` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 702 | `mocha --reporter spec` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 700 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 698 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 695 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 695 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 691 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 690 | `mocha test/**/test_*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 688 | `npm run lint && mocha test` | 
| [electron/apps](https://github.com/electron/apps) | 687 | `mocha --reporter spec test/human-data.js test/colors-spec.js && standard --fix` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 653 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 652 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 651 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 650 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 648 | `./node_modules/.bin/mocha --bail` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 647 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 645 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 642 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 641 | `nyc mocha` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 639 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 639 | `nyc --reporter=text --reporter=lcov mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 679 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 679 | `mocha --bail test/` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 679 | `npm -s run mocha && npm run -s lint` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 678 | `mocha -R spec` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 675 | `mocha --compilers js:babel-register` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 674 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 671 | `mocha --require babel-register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 669 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [shime/livedown](https://github.com/shime/livedown) | 668 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 