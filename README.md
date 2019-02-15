# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:48 02/15/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45189 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42401 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42227 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30906 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25785 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25248 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25237 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21547 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20174 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18596 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18104 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17970 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17575 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15376 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15060 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14732 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14023 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12568 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12538 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12360 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12354 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11635 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11314 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11237 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10942 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10871 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10701 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10590 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10451 | `mocha --harmony` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10871 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10701 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10590 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10451 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9871 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9815 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9715 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9582 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9478 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9454 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9347 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9109 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8950 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8885 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8786 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8708 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8611 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8588 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8481 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8408 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8317 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8277 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8212 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8069 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8048 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8041 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7979 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7959 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7898 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7616 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7592 | `mocha --compilers js:babel-core/register` | 
| [dthree/cash](https://github.com/dthree/cash) | 7584 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7564 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7557 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7536 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7287 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7208 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7131 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7075 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7008 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6925 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6415 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6333 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6289 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6249 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6230 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6177 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6119 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6057 | `standard && mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5943 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5903 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5819 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5809 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5796 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5722 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 5706 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5943 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5903 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5819 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5809 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5796 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5722 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 5706 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5660 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5615 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5591 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5442 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5427 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5401 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5374 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5367 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5171 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5135 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5132 | `mocha --color` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5093 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5064 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4989 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4975 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4950 | `nyc mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4924 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4921 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4894 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4869 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4857 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4849 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4752 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4702 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4653 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4585 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4565 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4486 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4463 | `mocha --timeout=15000 tests/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4459 | `NODE_ENV=test mocha --exit` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4433 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4402 | `mocha --check-leaks --reporter spec --bail` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4315 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4216 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4192 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4145 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4099 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4031 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4023 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3963 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3935 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3859 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3935 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3859 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3829 | `npm run build && mocha test/*.test.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3817 | `mocha && tsc -p ./test/types` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3804 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3773 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3746 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3738 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3717 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3677 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3676 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3634 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3601 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3590 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3777 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3773 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3759 | `eslint . && mocha -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3746 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3738 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3717 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3677 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3676 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3634 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3601 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3590 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3563 | `nyc mocha && tsc` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3496 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3494 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3463 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3449 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3434 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3418 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3407 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3398 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3388 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3352 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3337 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3319 | `mocha test/index.js && npm run demo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3204 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3177 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3172 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3171 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3120 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3103 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3084 | `npm run mocha && npm run lint` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3080 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3068 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3041 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3033 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3018 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3010 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2995 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2987 | `mocha --require @babel/register --recursive spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2980 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2972 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2971 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2962 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2918 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2915 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2907 | `mocha -R spec spec spec/reporters` | 
| [retejs/rete](https://github.com/retejs/rete) | 2852 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2850 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2847 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2826 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2795 | `mocha "./test/**/*-test.js"` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2312 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2264 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2245 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2229 | `mocha && eslint *.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2211 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2199 | `mocha test/runner.js --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2189 | `cross-env BABEL_ENV=test mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2166 | `mocha --compilers js:babel-register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2141 | `mocha --compilers js:babel-core/register __tests__` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2135 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2524 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2512 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2475 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2467 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2465 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2465 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2451 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2408 | `npm run build && mocha --require babel-register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2385 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2408 | `npm run build && mocha --require babel-register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2385 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2322 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2312 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2309 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2309 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2297 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2291 | `mocha test/**/*.coffee` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2271 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2264 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2245 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2235 | `npm run lint && mocha tests/**/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2229 | `mocha && eslint *.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2211 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2208 | `./node_modules/.bin/mocha && npm run jshint` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2199 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2195 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2166 | `mocha --compilers js:babel-register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2141 | `mocha --compilers js:babel-core/register __tests__` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2135 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2095 | `mocha test` | 
| [kach/nearley](https://github.com/kach/nearley) | 2082 | `mocha test/*.test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2062 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2055 | `npm run lint && mocha -R dot && npm run cover` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2045 | `mocha && npm run lint` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2028 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1974 | `mocha test/**/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1963 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1959 | `bmocha --reporter spec test/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1953 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1950 | `npm run lint && mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1897 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1890 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1976 | `mocha --require ./test/common --growl test/expect.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1974 | `mocha test/**/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1964 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1963 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1959 | `bmocha --reporter spec test/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1953 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1950 | `npm run lint && mocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1937 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1926 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1924 | `mocha test` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1915 | `mocha compiled_tests/` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1903 | `nyc mocha --timeout=20000 test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1839 | `eslint --cache . && tsc && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1834 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1832 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1821 | `mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1821 | `mocha test/setup.js test/spec/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1805 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1795 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1779 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1771 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1770 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1754 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1751 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1747 | `mocha test/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1805 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1795 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1782 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1779 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1771 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1770 | `npm run lint && mocha && npm run typescript` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1769 | `mocha ./test/test*.js --reporter spec` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1754 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1751 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1747 | `mocha test/*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1601 | `mocha -R spec ./test/unit/**` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1601 | `mocha test/unit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1590 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1588 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1582 | `mocha tests/test-*` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1546 | `node_modules/.bin/mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1545 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1535 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1531 | `npm run lint && mocha && karma start --single-run` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1528 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1526 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1511 | `mocha test/**/*.spec.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1502 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1501 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1494 | `standard && istanbul cover _mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1492 | `mocha --recursive test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1482 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1475 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1474 | `mocha --opts test/opts/mocha.opts` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1467 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1461 | `mocha test/tests.js --timeout=10000` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1455 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1601 | `mocha -R spec ./test/unit/**` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1601 | `mocha test/unit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1590 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1588 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1580 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1556 | `mocha --check-leaks --require @babel/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1531 | `npm run lint && mocha && karma start --single-run` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1528 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1526 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1521 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1512 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1511 | `mocha test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1507 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1507 | `mocha -R spec test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1502 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1501 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1494 | `standard && istanbul cover _mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1492 | `mocha --recursive test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1482 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1433 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1432 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1417 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1417 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1411 | `webpack && npm run lint && npm run mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1407 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1397 | `mocha --check-leaks --reporter spec --bail test/` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1396 | `npm run mocha:istanbul` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1396 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1387 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1381 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1377 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1373 | `NODE_PATH=. mocha **/*.spec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1373 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1372 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1372 | `cross-env NODE_ENV=test nyc mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1371 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1362 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1354 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1324 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1317 | `mocha src/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1317 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1313 | `npm run lint && npm run mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1311 | `mocha --timeout 30000 --recursive ./tests` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1309 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1306 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1306 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1302 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1299 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1294 | `istanbul test _mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1290 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1272 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1295 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1294 | `istanbul test _mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1290 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1280 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [variety/variety](https://github.com/variety/variety) | 1280 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1272 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1271 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1258 | `mocha --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1256 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1258 | `mocha --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1256 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1244 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1241 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1237 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1235 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1228 | `node ./node_modules/mocha/bin/mocha tests` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1192 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1189 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1187 | `xo && mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1176 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1175 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1175 | `mocha --reporter spec test --recursive` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1164 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1155 | `istanbul cover _mocha test/*.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1102 | `mocha --recursive --bail --reporter spec test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1099 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1082 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1078 | `npm run lint && npm run mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1077 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1073 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1120 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1102 | `mocha --recursive --bail --reporter spec test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1099 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1009 | `npm run lint && mocha -R spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1008 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1007 | `./node_modules/.bin/mocha -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1006 | `mocha --compilers js:babel-register test/*.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 998 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 994 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 986 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 982 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 976 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 975 | `mocha -t 600000` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1078 | `npm run lint && npm run mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1077 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1073 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1053 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1047 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 874 | `mocha --harmony tests/**` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 872 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 870 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 865 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 862 | `npm run lint && mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 861 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 859 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 854 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 853 | `mocha -r babel-register --check-leaks test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 852 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 845 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 844 | `nyc mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 844 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 841 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 838 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 837 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 833 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 832 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 832 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 831 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 830 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 825 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 824 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 823 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 822 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 814 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 811 | `_mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 811 | `mocha test/mocha.js test/crc/index.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 808 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 807 | `mocha test` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 807 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 806 | `mocha test` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 806 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 804 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 804 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 801 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 800 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 797 | `mocha --no-timeouts` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 794 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 793 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 787 | `mocha --recursive -s 15 test/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 779 | `mocha tests --timeout 10000` | 
| [koajs/static](https://github.com/koajs/static) | 778 | `mocha --harmony --reporter spec --exit` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 776 | `mocha ./unittest` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 774 | `babel-node node_modules/.bin/_mocha -- test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 761 | `./bin/selenium-standalone install && mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 754 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 753 | `mocha 'test/**/*.tests.js'` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 751 | `./node_modules/.bin/mocha tests/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 745 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 743 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 745 | `npm run test-mocha && npm run test-karma` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 743 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 739 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 737 | `mocha --compilers js:babel-core/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 736 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [electron/apps](https://github.com/electron/apps) | 735 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 735 | `mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 734 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 733 | `mocha --reporter spec test/` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 707 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 706 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 705 | `mocha` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 701 | `mocha --reporter spec` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 699 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 692 | `_mocha -u bdd --colors test/` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 692 | `npm -s run mocha && npm run -s lint` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 739 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 737 | `mocha --compilers js:babel-core/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 736 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [electron/apps](https://github.com/electron/apps) | 735 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 735 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 735 | `mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 734 | `mocha ./test/test.js --timeout 1000000` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 734 | `mocha --reporter spec --bail --check-leaks test/` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 733 | `mocha --reporter spec test/` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 729 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 729 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 711 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 707 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 704 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 703 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 701 | `mocha --reporter spec` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 699 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 660 | `mocha --recursive --compilers js:babel-core/register` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 659 | `nyc mocha && nyc report -r html mocha` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 659 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 659 | `mocha --ui bdd --reporter spec` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 658 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 658 | `node_modules/.bin/mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 658 | `mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 656 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 656 | `mocha` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 654 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 653 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 653 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 653 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 652 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 650 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 650 | `./node_modules/.bin/mocha --bail` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 647 | `nyc mocha` | 