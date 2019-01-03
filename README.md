# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:21 01/03/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44766 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41914 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41714 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30760 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25089 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24766 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21182 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19952 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18270 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17825 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17665 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16861 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14994 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14789 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14637 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13823 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13507 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12955 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12762 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12714 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12684 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12353 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12256 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12198 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12169 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11365 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11018 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10885 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10781 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10650 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10526 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10386 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10290 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9663 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9649 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9573 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9428 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9399 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9283 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9248 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8828 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8727 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8654 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8545 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8532 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8507 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8433 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8364 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8224 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8017 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7964 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7928 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7924 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7797 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7786 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7772 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7586 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7573 | `npm run build && istanbul cover _mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7528 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7458 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7445 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7388 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7370 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7326 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7090 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7073 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6938 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6751 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6695 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6517 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6501 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6371 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6240 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6191 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6173 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6138 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6105 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6073 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6067 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6060 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5889 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5855 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5684 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5646 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5602 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5585 | `npm run lint && mocha tests/**/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5527 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5465 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5448 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5317 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5298 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5265 | `mocha test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5204 | `mocha src/**/*Tests.js --harmony` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5172 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 5162 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5106 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4976 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4921 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4906 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4862 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4860 | `nyc mocha --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4857 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4854 | `./node_modules/.bin/mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4837 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4833 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4814 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4792 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4790 | `npm run lint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4738 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4736 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4576 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4539 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4533 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4514 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4514 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4475 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4374 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4366 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4317 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4266 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4263 | `mocha --check-leaks --reporter spec --bail` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4227 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4227 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4225 | `NODE_ENV=test mocha --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4199 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4125 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4097 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4065 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4012 | `nyc mocha "test/**/*.test.js"` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3864 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3826 | `NODE_ENV=test mocha test/**/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3812 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3795 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3729 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3709 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3687 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3682 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3638 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3629 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3611 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3583 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3565 | `eslint . && mocha -t 5000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3499 | `nyc mocha && tsc` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3492 | `mocha && tsc -p ./test/types` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3465 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3418 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3416 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3400 | `npm run mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3397 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3354 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3348 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3340 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3182 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3177 | `./node_modules/.bin/mocha test/test.*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3176 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3162 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3141 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3087 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3067 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3059 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3055 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3011 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2993 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2974 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2970 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2951 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2948 | `mocha test-node` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3177 | `./node_modules/.bin/mocha test/test.*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3176 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3162 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3141 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3135 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3087 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3067 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3059 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3011 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2993 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2974 | `node_modules/.bin/mocha --reporter spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2973 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2951 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2782 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2755 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2753 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2744 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2734 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2724 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2715 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2698 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2697 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2679 | `nyc mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2646 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2642 | `mocha test/unit --require mochahook` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2631 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2607 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2168 | `mocha && eslint *.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2146 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2120 | `mocha --compilers js:babel-core/register __tests__` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2092 | `mocha --compilers js:babel-register` | 
| [kach/nearley](https://github.com/kach/nearley) | 2027 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2021 | `npm run lint && mocha -R dot && npm run cover` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2010 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2009 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2368 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2365 | `npm run build && mocha --require babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2317 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2298 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2263 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2241 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2224 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2224 | `standard && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2365 | `npm run build && mocha --require babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2317 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2308 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2303 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2263 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2120 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2117 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2104 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2092 | `mocha --compilers js:babel-register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2043 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2021 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2014 | `npm run mocha && npm run karma` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2010 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2009 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [then/promise](https://github.com/then/promise) | 2000 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1998 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1983 | `mocha && npm run lint` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1960 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1957 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1944 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1942 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1938 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1931 | `bmocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1922 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1922 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1905 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1893 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1889 | `mocha test` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1874 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1871 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1859 | `mocha compiled_tests/` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1852 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1848 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1838 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1797 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1795 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1790 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1786 | `npm run lint && npm run mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1769 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1767 | `eslint --cache . && tsc && mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1767 | `nyc mocha --timeout=20000 test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1746 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1740 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1737 | `mocha tests.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1735 | `./node_modules/.bin/mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1734 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1733 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1728 | `mocha test/*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1723 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1720 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1713 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1709 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1702 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1701 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1682 | `mocha test/test-*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1679 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1679 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1675 | `mocha && size-limit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1670 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1662 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1661 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1620 | `mocha ./test/test*.js --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1618 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1617 | `mocha --reporter spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1611 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1607 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1607 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1606 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1604 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1596 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1588 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1588 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1585 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1573 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1564 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1585 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1573 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1564 | `nyc mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1562 | `mocha test/unit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1540 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1536 | `mocha -u tdd` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1421 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1415 | `npm run build && mocha -r should` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1414 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1404 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1389 | `mocha --recursive test/bin` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1387 | `mocha test --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1380 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1378 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1373 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1365 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1308 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1306 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1304 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1302 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1302 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1289 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1286 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1285 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1283 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1281 | `istanbul test _mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1270 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1268 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1267 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1263 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1255 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1344 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1343 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1339 | `mocha --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1338 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1334 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1327 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1326 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1325 | `npm run mocha:istanbul` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1322 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1322 | `webpack && npm run lint && npm run mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1316 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1314 | `mocha test/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1313 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1308 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1306 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1306 | `npm run lint && mocha --require @babel/register` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1304 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1302 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1302 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1300 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1290 | `mocha tests/` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1289 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1286 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1283 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1280 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1270 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1268 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1268 | `mocha --timeout 30000 --recursive ./tests` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1267 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1266 | `mocha --timeout 20000` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1264 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [variety/variety](https://github.com/variety/variety) | 1263 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1244 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1239 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1239 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1236 | `mocha --reporter spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1227 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1221 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1210 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1206 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1181 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1179 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1174 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1165 | `mocha $(find test -name '*.test.js') --exit` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1163 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1160 | `npm-run-all test:jest test:server:mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1159 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1158 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1157 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1141 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1139 | `webpack && mocha test/unit` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1131 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1116 | `mocha --reporter spec test --recursive` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1114 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1114 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1113 | `standard && mocha -b` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1111 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1110 | `mocha test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1101 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1101 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1100 | `npm run convertto:es5 && npm run mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1096 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1093 | `mocha --recursive --bail --reporter spec test` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1042 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1024 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1015 | `mocha --colors ./test/*.spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1013 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1007 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1003 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 990 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1063 | `mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1062 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1057 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1054 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1057 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1054 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1042 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1042 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1024 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1024 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1015 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1013 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1013 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1007 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 894 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 891 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 879 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 874 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 868 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 866 | `eslint test && mocha --compilers js:babel/register` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 864 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 862 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 928 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 927 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 923 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 916 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 915 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 914 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 914 | `mocha -t 5000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 905 | `npm run lint && npm run mocha:no-functional` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 905 | `./node_modules/.bin/mocha test/**/*` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 902 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 899 | `mocha test/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 891 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 887 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 881 | `node_modules/.bin/mocha test/spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 879 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 874 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 863 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 862 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 860 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 858 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 857 | `mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 857 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 855 | `mocha -r should --exit test/*.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 851 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 847 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 844 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 843 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 838 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 838 | `mocha --async-only` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 836 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 851 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 847 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 844 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 843 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 842 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 842 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 838 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 838 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 838 | `mocha --async-only` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 836 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 834 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 833 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 836 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 834 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 833 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [developit/decko](https://github.com/developit/decko) | 832 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 832 | `mocha --harmony tests/**` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 831 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 829 | `mocha test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 825 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 824 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 822 | `nyc mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 822 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 818 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 772 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 768 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 762 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 753 | `./bin/selenium-standalone install && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 750 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 769 | `mocha tests --timeout 10000` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 768 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 763 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 762 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 762 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 762 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 761 | `standard && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 754 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 772 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 772 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 769 | `mocha tests --timeout 10000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 763 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 762 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 762 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 761 | `standard && mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 772 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 769 | `mocha tests --timeout 10000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 768 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 763 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 762 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 762 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 762 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 761 | `standard && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 754 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 753 | `./bin/selenium-standalone install && mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 752 | `mocha test` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 752 | `mocha --reporter spec build/test/index.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 752 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 750 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 747 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 744 | `eslint . && mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 743 | `mocha test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 741 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 727 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 725 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 723 | `mocha --compilers js:babel-core/register` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 723 | `mocha 'test/**/*.tests.js'` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 721 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 720 | `mocha --reporter spec test/` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 713 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 712 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 