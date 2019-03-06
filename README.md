# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:30 03/06/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45385 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42703 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42389 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30968 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25954 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25507 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25297 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21778 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20289 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18780 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18780 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18283 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18125 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17868 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15544 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15183 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14779 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14125 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13886 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13445 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13081 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12933 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12877 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12741 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12682 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12447 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12378 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11744 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11504 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11323 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11025 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10767 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10728 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10488 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9999 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9880 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9749 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9641 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9560 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9487 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9390 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9271 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9006 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8594 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8540 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8505 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8340 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8297 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8290 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8183 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8135 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8100 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8089 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8056 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7963 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7668 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7659 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7654 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7636 | `mocha; jshint *.js lib` | 
| [dthree/cash](https://github.com/dthree/cash) | 7589 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7587 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7668 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7659 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7654 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7636 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7624 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7589 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7587 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7345 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7154 | `mocha $HARMONY_OPTS` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7141 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7123 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7036 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6627 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6435 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6415 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6406 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6335 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6327 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6261 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6221 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6205 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6164 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6149 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6067 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5961 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5953 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5924 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5924 | `mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5917 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5826 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5753 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5743 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5694 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5628 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5516 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5482 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5460 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5413 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5352 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5150 | `mocha --recursive` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5140 | `gulp lint && mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5133 | `npm run lint && npm run mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5128 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5072 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5041 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5000 | `gulp build; mocha;` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4980 | `NODE_ENV=test mocha --exit` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4969 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4931 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4915 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4884 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4883 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4866 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4785 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4762 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4694 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4590 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4573 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4514 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4497 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4490 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4453 | `mocha --check-leaks --reporter spec --bail` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4393 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4264 | `npm run build && cd test && mocha . --reporter dot` | 
| [tj/ejs](https://github.com/tj/ejs) | 4112 | `mocha --require should --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4013 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3978 | `NODE_ENV=test mocha test/**/*.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3752 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3752 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3684 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3682 | `node_modules/.bin/mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3606 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3876 | `eslint . && mocha -t 5000` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3853 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3838 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3835 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3834 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3809 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3752 | `mocha test/* --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3684 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3682 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3602 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3571 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3524 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3523 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3469 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3672 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3611 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3606 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3602 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3571 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3524 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3523 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3469 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3453 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3447 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3496 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3469 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3453 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3447 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3437 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3431 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3429 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3427 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3388 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3379 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2924 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2921 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2920 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2875 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2793 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2771 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2765 | `xo && mocha` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2751 | `cross-env TEST_WATCH=1 TEST_BROWSER_DRIVER=chrome meteor test --once --driver-package meteortesting:mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2725 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2711 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2703 | `mocha --timeout 100000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3137 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3123 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3110 | `npm run mocha && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3071 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3069 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3051 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3042 | `mocha test-node` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3033 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3026 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3022 | `mocha --require @babel/register --recursive spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3016 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3013 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2992 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2983 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2981 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2940 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2939 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2477 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2458 | `mocha -R spec test/*.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2453 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2429 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2409 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2389 | `grunt jshint && mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2373 | `npm run lint && npm run mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2349 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2338 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2336 | `mocha test/**/*.coffee` | 
| [gajus/swing](https://github.com/gajus/swing) | 2332 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2290 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2771 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2765 | `xo && mocha` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2751 | `cross-env TEST_WATCH=1 TEST_BROWSER_DRIVER=chrome meteor test --once --driver-package meteortesting:mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2746 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2744 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2725 | `mocha --recursive --watch` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2720 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2711 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2703 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2684 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2651 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2636 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2537 | `mocha test/index.js --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2536 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2525 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2505 | `nyc --require babel-register npm run _mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2496 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2477 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2458 | `mocha -R spec test/*.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2453 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2453 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2429 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2409 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2112 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2112 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [kach/nearley](https://github.com/kach/nearley) | 2107 | `mocha test/*.test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2074 | `mocha tests --require @babel/register` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2059 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2057 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2045 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2028 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2027 | `mocha --recursive` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2023 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [then/promise](https://github.com/then/promise) | 2023 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1997 | `mocha test/**/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1984 | `mocha --reporter spec && npm run test-typescript` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1971 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1971 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1969 | `npm run lint && mocha --reporter spec test/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1966 | `nyc mocha --timeout=20000 test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1944 | `mocha --reporter spec --grep .` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1940 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1937 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1911 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1907 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1883 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1911 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1907 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1883 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1863 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1862 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1848 | `mocha ./test/test*.js --reporter spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1848 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1835 | `mocha test/setup.js test/spec/*.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1691 | `mocha && size-limit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1683 | `NODE_ENV=test mocha tests/*.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1674 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1669 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1667 | `mocha spec` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1639 | `mocha --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1629 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1627 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1627 | `./node_modules/mocha/bin/mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1625 | `mocha -R spec ./test/unit/**` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1619 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1613 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1609 | `mocha tests/test-*` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1758 | `mocha test/*.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1756 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1755 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1748 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1747 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1735 | `mocha test --timeout 600000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1734 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1725 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1723 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1722 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1627 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1627 | `./node_modules/mocha/bin/mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1625 | `mocha -R spec ./test/unit/**` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1619 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1613 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1609 | `mocha tests/test-*` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1561 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1557 | `node_modules/.bin/mocha --recursive` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1557 | `node_modules/.bin/mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1550 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1545 | `mocha -u tdd` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1536 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1533 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1530 | `mocha --recursive test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1530 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1522 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1522 | `mocha test/**/*.spec.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1521 | `mocha -R spec test/*.js` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1517 | `mocha test --compilers js:babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1512 | `npm run prepublishOnly && mocha test/test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1510 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1499 | `mocha --reporter dot` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1517 | `mocha test --compilers js:babel-core/register` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1513 | `standard && istanbul cover _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1512 | `npm run prepublishOnly && mocha test/test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1510 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1499 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1490 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1487 | `mocha --opts test/opts/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1473 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1455 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1161 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1158 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1155 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1137 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1134 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1117 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1109 | `mocha --recursive --bail --reporter spec test` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1102 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1101 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 984 | `mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 982 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 981 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 970 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 969 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 963 | `standard && standard ./bin/* && mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 963 | `./node_modules/.bin/mocha test/**/*` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 952 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 947 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 944 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1417 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1414 | `npm run mocha:istanbul` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1405 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1402 | `mocha --recursive` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1397 | `mocha --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1397 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1396 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1396 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1390 | `NODE_PATH=. mocha **/*.spec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1387 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1385 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1374 | `cross-env NODE_ENV=test nyc mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1374 | `npm run lint && mocha --require @babel/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1372 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1353 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1351 | `mocha tests/` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1349 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1349 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1346 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1343 | `lerna run test && mocha` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1343 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1340 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1337 | `npm run lint && npm run mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1337 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1336 | `mocha --timeout 60000 test/` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1335 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1335 | `mocha --timeout 20000` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1334 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1333 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1333 | `mocha --timeout 30000 --recursive ./tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1333 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1329 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1293 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1288 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1279 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1261 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1253 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1249 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1279 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1275 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1261 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1253 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1249 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1219 | `mocha --recursive -r tests/setup tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1213 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1211 | `mocha --reporter spec test --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1209 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1206 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1199 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1194 | `xo && mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1184 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1180 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1178 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1177 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1140 | `npm run lint && npm run mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1137 | `standard && mocha -b` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1133 | `mocha test/*` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1133 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1112 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1101 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1065 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1061 | `mocha test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1040 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1039 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1031 | `mocha --reporter spec --bail --check-leaks test/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1029 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1028 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1026 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1024 | `npm run lint && mocha -R spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1021 | `./node_modules/.bin/mocha -R spec` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1039 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1031 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1031 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1029 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1026 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1024 | `npm run lint && mocha -R spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1019 | `mocha --async-only` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1012 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1010 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1008 | `mocha -R list` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1012 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1010 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1008 | `mocha -R list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1008 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 984 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 982 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 982 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 981 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 980 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 977 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1012 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1010 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1008 | `mocha -R list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1008 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 984 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1031 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1031 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1029 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1028 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1026 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1024 | `npm run lint && mocha -R spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1021 | `./node_modules/.bin/mocha -R spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1020 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1019 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1012 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1010 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1008 | `mocha -R list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1008 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 984 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 982 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 982 | `mocha tests` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 982 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 981 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 980 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 977 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 970 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 969 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 969 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 968 | `nyc mocha specs` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 968 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 964 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 963 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 963 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 963 | `standard && standard ./bin/* && mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 963 | `./node_modules/.bin/mocha test/**/*` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 887 | `npm run lint && mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 875 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 872 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 867 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 865 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 861 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 861 | `mocha -r babel-register --check-leaks test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 913 | `mocha -r should --exit test/*.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 911 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 909 | `npm run lint && npm run mocha:no-functional` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 902 | `npm run build && istanbul test _mocha test/test.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 898 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 895 | `mocha --harmony --full-trace --check-leaks` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 894 | `mocha --harmony tests/**` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 887 | `npm run lint && mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 886 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 909 | `npm run lint && npm run mocha:no-functional` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 902 | `npm run build && istanbul test _mocha test/test.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 898 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 896 | `mocha --timeout 200000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 895 | `mocha --harmony --full-trace --check-leaks` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 894 | `mocha --harmony tests/**` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 893 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 888 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 887 | `npm run lint && mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 886 | `mocha --reporter list` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 886 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 888 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 887 | `npm run lint && mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 886 | `mocha --reporter list` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 886 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 877 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 875 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 872 | `istanbul cover _mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 872 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 870 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 799 | `nyc mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 793 | `mocha --recursive -s 15 test/` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 786 | `nyc mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 779 | `babel-node node_modules/.bin/_mocha -- test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 810 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 810 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 808 | `eslint . && mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 804 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 798 | `xo && mocha -R spec` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 793 | `mocha --recursive -s 15 test/` | 
| [JoshKaufman/ursa](https://github.com/JoshKaufman/ursa) | 583 | `mocha --recursive --reporter spec` | 
| [csstree/csstree](https://github.com/csstree/csstree) | 581 | `mocha --reporter progress` | 
| [zpratt/react-tdd-guide](https://github.com/zpratt/react-tdd-guide) | 579 | `npm run lint && mocha */test` | 
| [nicksp/redux-webpack-es6-boilerplate](https://github.com/nicksp/redux-webpack-es6-boilerplate) | 578 | `mocha --compilers js:babel-core/register,css:./test/unit/cssNullCompiler.js --require ./test/unit/testHelper.js --recursive ./test/unit` | 
| [scniro/gulp-clean-css](https://github.com/scniro/gulp-clean-css) | 567 | `./node_modules/.bin/mocha ./index.spec.js` | 
| [azproduction/autopolyfiller](https://github.com/azproduction/autopolyfiller) | 566 | `npm run lint && mocha -R spec` | 
| [GoogleChrome/proxy-polyfill](https://github.com/GoogleChrome/proxy-polyfill) | 563 | `mocha` | 
| [jsantell/poet](https://github.com/jsantell/poet) | 561 | `./node_modules/.bin/mocha --reporter spec --ui bdd` | 
| [Gottwik/Enduro](https://github.com/Gottwik/Enduro) | 557 | `mocha --recursive --bail` | 
| [krasimir/stent](https://github.com/krasimir/stent) | 556 | `./node_modules/.bin/mocha --require babel-register --require babel-polyfill --require test/setup.js --require jsdom-global/register --reporter spec --slow 100 './src/**/**.spec.{js,jsx}'` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 805 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 804 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 802 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 799 | `nyc mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 798 | `xo && mocha -R spec` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 793 | `mocha --recursive -s 15 test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 