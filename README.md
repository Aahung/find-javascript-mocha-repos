# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:13 02/03/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45088 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42199 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42066 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30867 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25927 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25643 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25195 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25133 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21424 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20128 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17888 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17403 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15286 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14978 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14711 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13970 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13687 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13020 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12788 | `istanbul cover _mocha` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13687 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13180 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13020 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12788 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12786 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12491 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12466 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12356 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12305 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11547 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11195 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11179 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10908 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10831 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9787 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9775 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9542 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9442 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9415 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9328 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8963 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8914 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8766 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8697 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8598 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8573 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8459 | `grunt clean:test && mocha --exit` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8766 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8697 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8598 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8573 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8459 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8328 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8285 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8268 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8125 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8053 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8022 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7990 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7932 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7917 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7876 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7608 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7585 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7553 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7504 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7499 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7497 | `mocha; jshint *.js lib` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7449 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7203 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7180 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7111 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7045 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6910 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6882 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6402 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6291 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6279 | `mocha tests/node.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6257 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6221 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6212 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6105 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6018 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5932 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5891 | `mocha && eslint lib/**` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5775 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5770 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5768 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5737 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5704 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5626 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5574 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5572 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5414 | `mocha test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5395 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5346 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5316 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5124 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5088 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5060 | `mocha --recursive` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5316 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5124 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5088 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5060 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4992 | `npm run lint && npm run mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4963 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4959 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4949 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4917 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4896 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4888 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4860 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4852 | `mocha test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4845 | `nyc mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4838 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4750 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4659 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4595 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4581 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4556 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4484 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4443 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4386 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4383 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4378 | `NODE_ENV=test mocha --exit` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4371 | `node_modules/.bin/mocha test/tests.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4283 | `npm run lint ; mocha && mocha test/individual` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4193 | `mocha -R spec ./test --recursive` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4154 | `npm run build && cd test && mocha . --reporter dot` | 
| [muicss/mui](https://github.com/muicss/mui) | 4141 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4095 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4072 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4003 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 4003 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 3960 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3947 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4003 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 4003 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 3960 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3947 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3932 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3911 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3830 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3820 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3785 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3774 | `npm run mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3760 | `mocha && tsc -p ./test/types` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3683 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3670 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3668 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3613 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3601 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3594 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3583 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3490 | `node_modules/.bin/mocha test/lib/` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3486 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3476 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3017 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3003 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2965 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2951 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2946 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2917 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2909 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2901 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2842 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2837 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2823 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2764 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2764 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2761 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2757 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3257 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3235 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3227 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3226 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3214 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3210 | `mocha --require should --reporter spec` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3186 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3172 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3167 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3163 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3162 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3107 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3096 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3065 | `npm run mocha && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3061 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3060 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3052 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3039 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3020 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3017 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3003 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2997 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2981 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2966 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2965 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2951 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2946 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2917 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2909 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2901 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2899 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2557 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2550 | `mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2549 | `mocha test` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2536 | `mocha && eslint .` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2535 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2531 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2522 | `mocha --reporter=spec test/*-test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2499 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2497 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2457 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2454 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2445 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2441 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2418 | `mocha -R spec test/*.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2604 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2556 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2549 | `mocha test` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2536 | `mocha && eslint .` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2535 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2531 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2522 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2499 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2497 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2457 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2454 | `mocha -R spec` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2150 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2136 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2135 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2134 | `mocha --compilers js:babel-core/register __tests__` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2110 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2058 | `npm run mocha && npm run karma` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2046 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2041 | `mocha tests --require @babel/register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2023 | `mocha test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2021 | `mocha --reporter spec --timeout 5000` | 
| [noble/noble](https://github.com/noble/noble) | 2418 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2393 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2392 | `npm run build && mocha --require babel-register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2383 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2312 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2295 | `npm run lint && npm run mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2253 | `mocha test/**/*.coffee` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2252 | `standard && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2249 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2210 | `mocha && eslint *.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2208 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2197 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2190 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2186 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2157 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2148 | `mocha --compilers js:babel-register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2136 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2135 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2110 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2074 | `mocha test/*.test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2074 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2058 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2050 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2046 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2045 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2041 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2033 | `mocha && npm run lint` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2023 | `mocha test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2023 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2021 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2003 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1899 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1892 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1881 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1865 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1845 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1817 | `eslint --cache . && tsc && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1815 | `npm run lint && npm run mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1762 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1749 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1728 | `mocha test --timeout 600000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1725 | `mocha ./test/test*.js --reporter spec` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1723 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1719 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1717 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1715 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1714 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1815 | `npm run lint && npm run mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1807 | `mocha test/setup.js test/spec/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1797 | `mocha --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1782 | `mocha --recursive` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1780 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1769 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1762 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1760 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1749 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1747 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1652 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1641 | `NODE_ENV=test mocha tests/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1635 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1626 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1615 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1614 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1611 | `mocha --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1610 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1587 | `mocha test/unit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1682 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1665 | `mocha spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1657 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1652 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1641 | `NODE_ENV=test mocha tests/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1635 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1627 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1626 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1610 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1587 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1579 | `mocha -R spec ./test/unit/**` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1577 | `nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1575 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1558 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1558 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1587 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1579 | `mocha -R spec ./test/unit/**` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1577 | `nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1575 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1564 | `mocha tests/test-*` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1558 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1558 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1546 | `mocha --check-leaks --require @babel/register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1543 | `node_modules/.bin/mocha --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1543 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1541 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1528 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1525 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1524 | `npm run lint && npm run mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1524 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1520 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1519 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1508 | `mocha --timeout 10000 ./tests/lib.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1503 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1502 | `mocha -R spec test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1486 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1480 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1445 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1424 | `npm run build && mocha -r should` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1423 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [electron/devtron](https://github.com/electron/devtron) | 1415 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1397 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1395 | `mocha --check-leaks --reporter spec --bail test/` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1390 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1415 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1410 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1407 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1407 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1397 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1390 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1376 | `./node_modules/.bin/mocha test` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1375 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1369 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1363 | `mocha --compilers js:babel-core/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1397 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1395 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1391 | `webpack && npm run lint && npm run mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1390 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1376 | `npm run mocha:istanbul` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1376 | `./node_modules/.bin/mocha test` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1375 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1371 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1369 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1363 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1362 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1360 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1355 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1350 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1328 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1327 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1326 | `mocha spec/exec.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1325 | `mocha test/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1323 | `mocha tests/` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1323 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1318 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1318 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1318 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1314 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1314 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1310 | `npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1309 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1226 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1199 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1184 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1182 | `xo && mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1182 | `mocha --reporter spec --bail --check-leaks test/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1181 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1172 | `mocha test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1170 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1169 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1169 | `mocha $(find test -name '*.test.js') --exit` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1250 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1237 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1226 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1199 | `mocha --recursive -r tests/setup tests` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1187 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1184 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1182 | `xo && mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1182 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1182 | `mocha --reporter spec --bail --check-leaks test/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1181 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1146 | `webpack && mocha test/unit` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1136 | `npm run convertto:es5 && npm run mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1135 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1130 | `mocha test/*` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1128 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1102 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1101 | `eslint src test && mocha --compilers babel-register` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1095 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1090 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1085 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1069 | `npm run lint && npm run mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1068 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1067 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1067 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1062 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1049 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1032 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1027 | `mocha --reporter spec --timeout 3000` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1026 | `mocha --recursive ./test/*_spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1022 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1016 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1014 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1011 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1011 | `mocha spec/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 972 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 968 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 964 | `mocha tests` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 963 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 962 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 951 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 949 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 948 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 975 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 972 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 968 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 967 | `mocha -t 600000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 966 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 964 | `mocha tests` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 963 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 962 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 952 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 951 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 949 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 948 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 947 | `./node_modules/.bin/mocha test/**/*` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 943 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 877 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 867 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 863 | `mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 860 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 860 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 859 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 898 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 893 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 889 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 888 | `node_modules/.bin/mocha test/spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 886 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 885 | `mocha --harmony --full-trace --check-leaks` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 859 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 859 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 858 | `mocha --harmony tests/**` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 857 | `mocha --reporter spec --bail --check-leaks test/` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 856 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 855 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 850 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 849 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 848 | `npm run lint && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 847 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 845 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 843 | `mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 842 | `mocha -r babel-register --check-leaks test/index.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 842 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 811 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 807 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 807 | `mocha index.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 804 | `mocha test` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 803 | `mocha test/mocha.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 796 | `xo && mocha -R spec` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 795 | `mocha tests --timeout 10000` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 794 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 790 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 789 | `npm run lint && npm run mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 787 | `mocha test` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 782 | `eslint . && mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 776 | `jenkins-mocha ./tests/*.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 773 | `mocha --harmony --reporter spec --exit` | 