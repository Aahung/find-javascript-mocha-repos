# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:30 01/11/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44844 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41953 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41849 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30788 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25125 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24862 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21248 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20009 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18330 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17893 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17702 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16998 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15073 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14834 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14664 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13867 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13557 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12973 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12850 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12729 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12710 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12352 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12327 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12273 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12208 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11413 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11057 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10971 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10816 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10713 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10543 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10398 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10339 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9682 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9680 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9640 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9462 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9412 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9337 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9265 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8860 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8769 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8672 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8603 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8549 | `mocha --check-leaks -R dot` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8535 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8441 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8349 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8233 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8033 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8032 | `npm run eslint && npm run mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7976 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7975 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7847 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7818 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7813 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7372 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7111 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7096 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6967 | `npm run jshint && mocha test/` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6965 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6769 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6736 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6533 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6533 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6380 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6254 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6217 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6192 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6158 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6147 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6083 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6073 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6071 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5918 | `standard && mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5621 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5591 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5503 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5459 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5341 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5315 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5306 | `mocha test` | 
| [teambit/bit](https://github.com/teambit/bit) | 5252 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5218 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5206 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5111 | `gulp lint && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 5252 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5218 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5206 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5111 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5001 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4931 | `gulp build; mocha;` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4929 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4911 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4910 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4889 | `nyc mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4871 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4860 | `./node_modules/.bin/mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4847 | `mocha -R spec 'tests/app'` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4844 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [santinic/how2](https://github.com/santinic/how2) | 4836 | `mocha test` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4827 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4818 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4769 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4743 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4580 | `mocha ./test/runner.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4556 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4539 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4533 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4392 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4370 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4336 | `node_modules/.bin/mocha test/tests.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4319 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4299 | `mocha --check-leaks --reporter spec --bail` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4281 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4249 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4231 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4197 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4126 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4101 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4081 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4079 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4023 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3993 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3947 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3929 | `export TESTING=true; mocha --reporter list` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3929 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3899 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3860 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3850 | `NODE_ENV=test mocha test/**/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3818 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3802 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3736 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3719 | `mocha test/* --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3695 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3682 | `mocha && tsc -p ./test/types` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3651 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3638 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3637 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3615 | `eslint . && mocha -t 5000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3560 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3515 | `nyc mocha && tsc` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3507 | `npm run mocha` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3492 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3430 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3414 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3392 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3367 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3366 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3358 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3326 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3314 | `mocha -R landing test/index --exit` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3430 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3418 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3414 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3392 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3367 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3366 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3358 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3326 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3319 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3314 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3294 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3273 | `mocha test/index.js && npm run demo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3261 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3213 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3206 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3197 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3188 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3177 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3162 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3141 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3140 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3110 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3080 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3068 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3059 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3033 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3004 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2999 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2521 | `nyc --reporter=html --reporter=text mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2512 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2510 | `mocha --reporter=spec test/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2488 | `mocha && eslint .` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2447 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2439 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2438 | `mocha -R spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2431 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2391 | `nyc --require babel-register npm run _mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2323 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2318 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2707 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2698 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2687 | `nyc mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2654 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2650 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2634 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2616 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2576 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2551 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2543 | `mocha test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2431 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 2420 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2397 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2391 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2386 | `mocha -R spec test/*.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2378 | `grunt jshint && mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2376 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2376 | `npm run build && mocha --require babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2323 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2318 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2306 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2303 | `mocha --compilers js:babel-register` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2462 | `TEST=all mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2448 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2447 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2439 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2438 | `mocha -R spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2431 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 2420 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2397 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2391 | `nyc --require babel-register npm run _mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2378 | `grunt jshint && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2376 | `npm run build && mocha --require babel-register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2397 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2391 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2386 | `mocha -R spec test/*.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2378 | `grunt jshint && mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2376 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2376 | `npm run build && mocha --require babel-register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2323 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2318 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2306 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2303 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2286 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2267 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2242 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2236 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [pahen/madge](https://github.com/pahen/madge) | 2235 | `npm run lint && npm run mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2229 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2216 | `npm run lint && mocha tests/**/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2197 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2171 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2149 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2144 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2137 | `./node_modules/.bin/mocha && npm run jshint` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2127 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2118 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2105 | `mocha --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2072 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 2044 | `mocha test/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2042 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2035 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2023 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2018 | `mocha tests --require @babel/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2015 | `mocha --reporter spec --timeout 5000` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2015 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2010 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2003 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1998 | `mocha --require=test/test_helper.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1994 | `mocha && npm run lint` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1971 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1964 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1958 | `mocha --bail --reporter spec --check-leaks test/` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1940 | `mocha test/**/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1958 | `mocha --bail --reporter spec --check-leaks test/` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1953 | `mocha test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1946 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1940 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1940 | `mocha --reporter spec && npm run test-typescript` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1936 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1934 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1923 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1914 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1900 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1891 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1880 | `mocha test -u bdd -R spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1873 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1870 | `mocha compiled_tests/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1914 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1900 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1891 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1880 | `mocha test -u bdd -R spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1873 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1870 | `mocha compiled_tests/` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1857 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1855 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1836 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1824 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1804 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1797 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1791 | `npm run lint && npm run mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1788 | `nyc mocha --timeout=20000 test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1783 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1776 | `eslint --cache . && tsc && mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1774 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1687 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1687 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1682 | `mocha --check-leaks --reporter spec --bail` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1679 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1670 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1670 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1647 | `mocha ./test/test*.js --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1638 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1623 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1619 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1623 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1619 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1614 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1610 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1607 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1607 | `mocha --recursive` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1605 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1604 | `NODE_ENV=test mocha tests/*.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1600 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1594 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1568 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1567 | `nyc mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1416 | `mocha --recursive test` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1401 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1391 | `mocha --recursive` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1387 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1385 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1384 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1384 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1363 | `mocha --check-leaks --reporter spec --bail test/` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1362 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1479 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1462 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1458 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1453 | `mocha --reporter dot` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1452 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1449 | `mocha --opts test/opts/mocha.opts` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1444 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1443 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1424 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1422 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1420 | `npm run build && mocha -r should` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1408 | `mocha test --compilers js:babel-core/register` | 
| [electron/devtron](https://github.com/electron/devtron) | 1405 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1405 | `istanbul cover _mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1401 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1401 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1395 | `mocha --recursive test/bin` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1391 | `mocha --recursive` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1387 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1384 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1384 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1384 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1384 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1370 | `./node_modules/.bin/mocha test` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1363 | `mocha --check-leaks --reporter spec --bail test/` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1362 | `NODE_PATH=. mocha **/*.spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1350 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1347 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1347 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1343 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1343 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1338 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1336 | `npm run mocha:istanbul` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1335 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1334 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1338 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1336 | `npm run mocha:istanbul` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1335 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1334 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1327 | `lerna run test && mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1323 | `npm run lint && mocha --require @babel/register` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1317 | `mocha test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1315 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1312 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1312 | `mocha --timeout 60000 test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1310 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1310 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1306 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1306 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1302 | `mocha tests/` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1301 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1295 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1287 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1286 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1286 | `istanbul test _mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1284 | `mocha --timeout 30000 --recursive ./tests` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1283 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1281 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1280 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1279 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1279 | `mocha --timeout 20000` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1278 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1266 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [normalize/mz](https://github.com/normalize/mz) | 1242 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1239 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1233 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1232 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1227 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [electron/asar](https://github.com/electron/asar) | 1213 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1211 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1219 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [electron/asar](https://github.com/electron/asar) | 1213 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1211 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1202 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1184 | `mocha --recursive -r tests/setup tests` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1182 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1152 | `istanbul cover _mocha test/*.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1142 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1141 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1140 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1129 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1120 | `mocha test` | 
| [electron/spectron](https://github.com/electron/spectron) | 1118 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1117 | `standard && mocha -b` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1111 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1111 | `npm run convertto:es5 && npm run mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1101 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1101 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1096 | `mocha --recursive --bail --reporter spec test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1096 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1095 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1095 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1089 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1084 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1068 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 1064 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1061 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1058 | `mocha --async-only` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1048 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1018 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1016 | `mocha --colors ./test/*.spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1015 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1010 | `npm run lint && npm run mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1008 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1004 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1003 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 995 | `mocha --recursive ./test/*_spec.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 993 | `mocha spec/*.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 989 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 988 | `mocha --compilers js:babel-register test/*.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 986 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 985 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 984 | `./node_modules/.bin/mocha -R spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 979 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 978 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 976 | `mocha "client.test" --compilers js:babel-register` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 974 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 968 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 968 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 963 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 961 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 959 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 958 | `mocha tests` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 958 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 958 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 956 | `mocha -t 600000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 954 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 952 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 948 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 943 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 941 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 941 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 940 | `mocha --timeout 5000` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 938 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 937 | `nyc mocha specs` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 915 | `mocha -t 5000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 913 | `./node_modules/.bin/mocha test/**/*` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 904 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 902 | `mocha test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 896 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 893 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 904 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 903 | `mocha test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 896 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 893 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 883 | `node_modules/.bin/mocha test/spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 851 | `nyc mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 850 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 845 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 844 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 842 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 839 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 838 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 838 | `mocha --harmony tests/**` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 838 | `mocha --async-only` | 
| [developit/decko](https://github.com/developit/decko) | 835 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 835 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 857 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 856 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 851 | `nyc mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 850 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 845 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 845 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 845 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 844 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 842 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 838 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 838 | `mocha --async-only` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 838 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 838 | `mocha --harmony tests/**` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 838 | `mocha --async-only` | 
| [developit/decko](https://github.com/developit/decko) | 835 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 835 | `mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 833 | `mocha test` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 828 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 827 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 826 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 826 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 825 | `nyc mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 823 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 821 | `npm run lint && mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 795 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 791 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 790 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 787 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 787 | `npm run lint && npm run mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 786 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 786 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 780 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 779 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 779 | `mocha --recursive -s 15 test/` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 773 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 772 | `babel-node node_modules/.bin/_mocha -- test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 767 | `mocha --ui tdd --require ./test/__setup` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 767 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 765 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 765 | `npm run-script jshint && npm run-script mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 787 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 787 | `npm run lint && npm run mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 786 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 786 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 785 | `mocha test/mocha.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 782 | `nyc mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 780 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 779 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 779 | `mocha --recursive -s 15 test/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 774 | `mocha tests --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 773 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 