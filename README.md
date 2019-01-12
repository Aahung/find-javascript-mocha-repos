# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:15 01/12/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44853 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41958 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41862 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30792 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25699 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25127 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24870 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21253 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20013 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18335 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17902 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17712 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17022 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15085 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14842 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14667 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13871 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13565 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12972 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12863 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12730 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12714 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12352 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12336 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12284 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12209 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11416 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11063 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10978 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10821 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10719 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10551 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10398 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10344 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9688 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9682 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9646 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9466 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9412 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9341 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9266 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8862 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8769 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8673 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8609 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8550 | `mocha --check-leaks -R dot` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8541 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8441 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8350 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8234 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8039 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8033 | `npm run eslint && npm run mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7981 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7978 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7852 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7823 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7815 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7634 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7582 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7582 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7484 | `mocha --compilers js:babel-core/register` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7456 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7426 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7405 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7376 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7115 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7097 | `mocha $HARMONY_OPTS` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6980 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6970 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6776 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6745 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6533 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6383 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6254 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6225 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6193 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6158 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6153 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6082 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6076 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6070 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5921 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5871 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5714 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5662 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5648 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5629 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5595 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5506 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5462 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5345 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5317 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5311 | `mocha test` | 
| [teambit/bit](https://github.com/teambit/bit) | 5263 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5222 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5206 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5116 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5004 | `mocha --recursive` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4954 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4934 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4932 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4911 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4892 | `nyc mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4874 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4860 | `./node_modules/.bin/mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4847 | `mocha -R spec 'tests/app'` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4846 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [santinic/how2](https://github.com/santinic/how2) | 4838 | `mocha test` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4829 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4818 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4771 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4743 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4580 | `mocha ./test/runner.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4562 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4539 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4533 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4394 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4369 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4337 | `node_modules/.bin/mocha test/tests.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4328 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4304 | `mocha --check-leaks --reporter spec --bail` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4282 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4262 | `NODE_ENV=test mocha --exit` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4250 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4231 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4197 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4127 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4102 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4082 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4079 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4025 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3999 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3999 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3948 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3930 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3901 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3860 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3851 | `NODE_ENV=test mocha test/**/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3821 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3802 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3736 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3720 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3701 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3695 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3687 | `mocha && tsc -p ./test/types` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3652 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3638 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3636 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3622 | `eslint . && mocha -t 5000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3604 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3588 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3583 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3564 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3517 | `nyc mocha && tsc` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3516 | `npm run mocha` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3498 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3163 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3145 | `mocha --require should --reporter spec` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3142 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3110 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3069 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3059 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3036 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3005 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2989 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2987 | `node_modules/.bin/mocha --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2965 | `mocha test-node` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2956 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2953 | `mocha -R spec --recursive src/test` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2950 | `mocha --require @babel/register --recursive spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2899 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3239 | `mocha test/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3212 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3207 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3198 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3190 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3177 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3163 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3145 | `mocha --require should --reporter spec` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3142 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3141 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3110 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3081 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3069 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3059 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2989 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2987 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2973 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2965 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2958 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2956 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2953 | `mocha -R spec --recursive src/test` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2950 | `mocha --require @babel/register --recursive spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2935 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2911 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2903 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [github-tools/github](https://github.com/github-tools/github) | 2899 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2884 | `mocha -R spec spec spec/reporters` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2865 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2856 | `npm run build && cd test && mocha . --reporter dot` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2843 | `istanbul cover _mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2840 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2784 | `mocha --require should --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2775 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2760 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2754 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2742 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2733 | `mocha "./test/**/*-test.js"` | 
| [tj/should.js](https://github.com/tj/should.js) | 2730 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2730 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2706 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2699 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2687 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2685 | `mocha --timeout 100000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2656 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2652 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2635 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2620 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2635 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2620 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2577 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2551 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2544 | `mocha test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2532 | `mocha test --exit && npm run lint` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2529 | `mocha test/src/**/*.unit.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2513 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2500 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2231 | `standard && mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2216 | `npm run lint && mocha tests/**/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2202 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2183 | `cross-env BABEL_ENV=test mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2178 | `mocha && eslint *.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2178 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2174 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2171 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2149 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2144 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2142 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2128 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2119 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2110 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2324 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2318 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2305 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2304 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2286 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2267 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2242 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [pahen/madge](https://github.com/pahen/madge) | 2239 | `npm run lint && npm run mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2236 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2231 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2216 | `npm run lint && mocha tests/**/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2202 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2198 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2183 | `cross-env BABEL_ENV=test mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2178 | `mocha && eslint *.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2178 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2174 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2171 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2149 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2142 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2128 | `mocha --compilers js:babel-core/register __tests__` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2128 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2119 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2110 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2074 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 2047 | `mocha test/*.test.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2046 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2042 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2024 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2019 | `mocha tests --require @babel/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2017 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2015 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2011 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2005 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1998 | `mocha --require=test/test_helper.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1996 | `mocha && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1973 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1964 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1961 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1958 | `mocha --bail --reporter spec --check-leaks test/` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1956 | `mocha test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1946 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1804 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1797 | `nyc mocha --timeout=20000 test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1784 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1778 | `eslint --cache . && tsc && mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1774 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1744 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1741 | `mocha tests.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1738 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1736 | `npm run lint && mocha && npm run typescript` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1733 | `mocha test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1729 | `mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1727 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1857 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1856 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1837 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1824 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1804 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1798 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1797 | `nyc mocha --timeout=20000 test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1794 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1784 | `mocha test/setup.js test/spec/*.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1744 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1744 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [zeit/ms](https://github.com/zeit/ms) | 1741 | `mocha tests.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1738 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1736 | `npm run lint && mocha && npm run typescript` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1733 | `mocha test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1729 | `mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1727 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1725 | `mocha test --timeout 600000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1714 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1710 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1703 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1703 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1557 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1543 | `mocha -R spec ./test/unit/**` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1542 | `node_modules/.bin/mocha --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1538 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require babel-core/register --recursive --exit` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1536 | `mocha tests/test-*` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1532 | `mocha --check-leaks --require @babel/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1528 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1519 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1504 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1503 | `npm run lint && mocha && karma start --single-run` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1650 | `mocha ./test/test*.js --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1638 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1625 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1620 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1618 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1614 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1610 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1609 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1607 | `./node_modules/mocha/bin/mocha -R spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1606 | `NODE_ENV=test mocha tests/*.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1601 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1598 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1592 | `mocha --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1569 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1567 | `nyc mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1557 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1556 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1462 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1458 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1454 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1453 | `mocha --reporter dot` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1449 | `mocha --opts test/opts/mocha.opts` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1444 | `npm run prepublishOnly && mocha test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1444 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1443 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1427 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1422 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1420 | `npm run build && mocha -r should` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1417 | `mocha --recursive test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1410 | `mocha test --compilers js:babel-core/register` | 
| [electron/devtron](https://github.com/electron/devtron) | 1406 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1405 | `istanbul cover _mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1401 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1401 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1396 | `mocha --recursive test/bin` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1391 | `mocha --recursive` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1388 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1386 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1384 | `./node_modules/mocha/bin/mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1384 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1384 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1371 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1363 | `mocha --check-leaks --reporter spec --bail test/` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1361 | `NODE_PATH=. mocha **/*.spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1350 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1348 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1348 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1345 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1343 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1340 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1338 | `webpack && npm run lint && npm run mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1336 | `npm run mocha:istanbul` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1334 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1327 | `lerna run test && mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1326 | `npm run lint && mocha --require @babel/register` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1318 | `mocha test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1327 | `lerna run test && mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1326 | `npm run lint && mocha --require @babel/register` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1318 | `mocha test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1315 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1313 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1312 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1311 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1310 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1307 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1307 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1304 | `mocha tests/` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1301 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1295 | `npm run lint && npm run mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1281 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1281 | `mocha --timeout 20000` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1279 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1265 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1249 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1249 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [normalize/mz](https://github.com/normalize/mz) | 1242 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1233 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1227 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1222 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [electron/asar](https://github.com/electron/asar) | 1214 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1211 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1204 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1176 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1173 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1166 | `mocha $(find test -name '*.test.js') --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1162 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1160 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1160 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1156 | `mocha --compilers js:@babel/register` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1152 | `istanbul cover _mocha test/*.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1143 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1141 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1140 | `webpack && mocha test/unit` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1156 | `mocha --compilers js:@babel/register` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1152 | `istanbul cover _mocha test/*.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1141 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1140 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1129 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1120 | `mocha --reporter spec test --recursive` | 
| [electron/spectron](https://github.com/electron/spectron) | 1117 | `mocha && standard` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1018 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1015 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1013 | `mocha test/*.test.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1011 | `npm run lint && npm run mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1004 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1003 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 996 | `mocha --recursive ./test/*_spec.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 993 | `mocha spec/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 992 | `npm run lint && mocha -R spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 991 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1072 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 1064 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1061 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1059 | `mocha --async-only` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 941 | `mocha test --compilers js:babel-register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 940 | `mocha --timeout 5000` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 938 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 938 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 935 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 928 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 924 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 921 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 916 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 916 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 915 | `mocha -t 5000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 915 | `./node_modules/.bin/mocha test/**/*` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 904 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 903 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 902 | `mocha test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 896 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 894 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 892 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 883 | `node_modules/.bin/mocha test/spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 881 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 878 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 877 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 876 | `npm run build && istanbul test _mocha test/test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 875 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 871 | `mocha --harmony --full-trace --check-leaks` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 871 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 869 | `mocha --reporter list` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 869 | `mocha -r should --exit test/*.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 862 | `istanbul cover _mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 860 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 862 | `istanbul cover _mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 860 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 856 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 852 | `nyc mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 851 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 845 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 845 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 845 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 792 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 787 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 787 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 786 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 786 | `npm run lint && npm run mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 785 | `mocha test/mocha.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 784 | `nyc mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 799 | `mocha test` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 790 | `mocha index.test.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 787 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 787 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 785 | `mocha test/mocha.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 795 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 792 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 791 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 787 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 787 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 786 | `npm run lint && npm run mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 785 | `mocha test/mocha.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 784 | `nyc mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 782 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 774 | `mocha tests --timeout 10000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 772 | `babel-node node_modules/.bin/_mocha -- test` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 768 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 767 | `mocha --ui tdd --require ./test/__setup` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 765 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 765 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [susam/texme](https://github.com/susam/texme) | 765 | `standard && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 764 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 764 | `npm run-script jshint && npm run-script mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 765 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [susam/texme](https://github.com/susam/texme) | 765 | `standard && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 764 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 764 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 763 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 761 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 760 | `mocha --harmony --reporter spec --exit` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 759 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 758 | `mocha test` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 756 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 756 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 755 | `./bin/selenium-standalone install && mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 754 | `eslint . && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 753 | `mocha --reporter spec build/test/index.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 753 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 765 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 765 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [susam/texme](https://github.com/susam/texme) | 765 | `standard && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 764 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 764 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 763 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 761 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 760 | `mocha --harmony --reporter spec --exit` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 759 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 758 | `mocha test` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 756 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 756 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 755 | `./bin/selenium-standalone install && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 754 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 754 | `eslint . && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 753 | `mocha --reporter spec build/test/index.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 690 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 689 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 688 | `mocha test/**/test_*.js` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 682 | `./node_modules/.bin/mocha` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 681 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 679 | `mocha -R spec` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 679 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 678 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 678 | `mocha --bail test/` | 