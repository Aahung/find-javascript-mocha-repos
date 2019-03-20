# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:42 03/20/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [expressjs/express](https://github.com/expressjs/express) | 42927 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42477 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31007 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26076 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25342 | `npm run lint && npm run mocha-node-test` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20368 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18956 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18393 | `mocha` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18956 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18393 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18210 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18038 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15698 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15279 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14813 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14182 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13103 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12907 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12840 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12780 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12493 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12383 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11826 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11649 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11409 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11092 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10869 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10526 | `mocha --harmony` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9921 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9695 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9641 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9513 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9411 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9384 | `mocha --opts mocha.opts` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9124 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9118 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9046 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8754 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8681 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8648 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8600 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8527 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8445 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8321 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8297 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9046 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8754 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8681 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8648 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8600 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8527 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8445 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8321 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8297 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8288 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8206 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8132 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8121 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8118 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 7992 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7772 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7758 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7711 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7702 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7699 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7644 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7599 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7387 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7267 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7174 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7155 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7104 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6659 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6458 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6450 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6382 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6356 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6318 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6285 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6277 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6228 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6167 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6163 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5127 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5093 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5013 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4934 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4898 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4850 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4765 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4722 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4653 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4601 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4574 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4532 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4495 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5441 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5211 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5175 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5153 | `gulp lint && mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5127 | `NODE_ENV=test mocha --exit` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5127 | `nyc mocha --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5124 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5093 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5013 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4998 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4934 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4923 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4898 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4892 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4874 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4850 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4765 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4722 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4653 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4601 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4594 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4574 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4544 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4532 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4495 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4493 | `mocha --check-leaks --reporter spec --bail` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4399 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4286 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [tj/ejs](https://github.com/tj/ejs) | 4130 | `mocha --require should --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4058 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3851 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3832 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3770 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3702 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3701 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4016 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3982 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3957 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3939 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3855 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3851 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3847 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3839 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3832 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3779 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3761 | `mocha test/* --reporter spec` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3761 | `mocha test/* --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3702 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3701 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3695 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3672 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3630 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3622 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3619 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3610 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3607 | `mocha tests/javascript` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3606 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3567 | `mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3542 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3512 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3503 | `node_modules/.bin/mocha test/lib/` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3243 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3203 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3194 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3184 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3161 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3137 | `nyc mocha --recursive` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3095 | `node_modules/.bin/mocha --reporter spec` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3074 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3073 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3069 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3065 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3045 | `mocha --require @babel/register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3032 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2998 | `mocha -R spec --recursive src/test` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2988 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2957 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2116 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2092 | `mocha && npm run lint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2062 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2020 | `mocha --require=test/test_helper.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1999 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1980 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1974 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1937 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1886 | `mocha tests.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2809 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2775 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2774 | `xo && mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2764 | `nyc mocha` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2764 | `cross-env TEST_BROWSER_DRIVER=chrome BABEL_ENV=coverage COVERAGE=1 COVERAGE_OUT_LCOVONLY=1 COVERAGE_APP_FOLDER=$PWD/ meteor test --once --driver-package meteortesting:mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2749 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2742 | `mocha test/unit --require mochahook` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2733 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2725 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2707 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2650 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2643 | `TEST=all mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2136 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2120 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2116 | `mocha tests --require @babel/register` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2080 | `mocha --recursive` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2066 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2057 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2031 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2017 | `mocha test/**/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2017 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1983 | `mocha --require ./test/common --growl test/expect.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1979 | `mocha tests.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2072 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2066 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2062 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2057 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2031 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2020 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2017 | `mocha test/**/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1979 | `mocha tests.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1975 | `mocha --bail --reporter spec --check-leaks test/` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1960 | `mocha --reporter spec --grep .` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1949 | `mocha test` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1449 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1434 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1433 | `mocha --check-leaks --reporter spec --bail test/` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1411 | `mocha --compilers js:babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1406 | `mocha --recursive` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1394 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1379 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2325 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2322 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2295 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [share/sharedb](https://github.com/share/sharedb) | 2286 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2272 | `mocha test/test-*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2266 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2229 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2225 | `mocha --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2221 | `mocha test/runner.js --reporter spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2203 | `mocha test` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2194 | `cross-env BABEL_ENV=test mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2180 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2176 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2171 | `mocha --compilers js:babel-core/register __tests__` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2170 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2164 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2136 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2120 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2116 | `mocha tests --require @babel/register` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2066 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2057 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2017 | `mocha test/**/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2017 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1999 | `mocha --reporter spec && npm run test-typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1979 | `mocha tests.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1975 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1974 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1960 | `mocha --reporter spec --grep .` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1949 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1941 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1925 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1882 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1869 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1864 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1863 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1826 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1937 | `mocha ./test/basic.js -t 5000` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1925 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1920 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1894 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1886 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1882 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1869 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1864 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1863 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1781 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1778 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1771 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1768 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1767 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1766 | `mocha test/*.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1754 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1747 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1739 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1737 | `mocha test --timeout 600000` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1732 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1729 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1725 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1647 | `mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1638 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1631 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1630 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1624 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1617 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1590 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1575 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1569 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1564 | `npm run lint && mocha && karma start --single-run` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1562 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1663 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1650 | `mocha --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1648 | `mocha -R spec ./test/unit/**` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1647 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1647 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1644 | `mocha test/unit` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1638 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1631 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1630 | `./node_modules/mocha/bin/mocha -R spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1629 | `mocha tests/test-*` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1624 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1617 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1491 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1455 | `npm run mocha:istanbul` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1451 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1449 | `webpack && npm run lint && npm run mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1449 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1447 | `npm run build && mocha -r should` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1434 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1433 | `mocha --check-leaks --reporter spec --bail test/` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1427 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1358 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1357 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1354 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1350 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1346 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1345 | `lerna run test && mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1342 | `npm run lint && npm run mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1342 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1339 | `mocha src/test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1339 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1339 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1538 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1532 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1532 | `mocha --timeout 10000 ./tests/lib.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1530 | `npm run prepublishOnly && mocha test/test.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1530 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1528 | `mocha test/**/*.spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1525 | `standard && istanbul cover _mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1518 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1513 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1507 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1500 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1495 | `mocha --opts test/opts/mocha.opts` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1491 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1451 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1449 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1434 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1427 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1411 | `mocha --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1406 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1377 | `cross-env NODE_ENV=test nyc mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1368 | `mocha tests/` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1358 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1357 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1354 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1349 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1346 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1342 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1339 | `mocha src/test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1339 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1315 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1315 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1303 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1305 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1302 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1284 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1269 | `mocha --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1261 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1261 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1256 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1226 | `mocha --reporter spec test --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1269 | `mocha --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1261 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1261 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1256 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1226 | `mocha --reporter spec test --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1284 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1272 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1269 | `mocha --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1261 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1261 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1256 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1261 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1261 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1256 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1232 | `node ./node_modules/mocha/bin/mocha tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1226 | `mocha --reporter spec test --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1193 | `npm run lint && npm run mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1188 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1187 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1184 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1183 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1177 | `npm run convertto:es5 && npm run mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1172 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1170 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1170 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1164 | `istanbul cover _mocha test/*.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1172 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1170 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1170 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1164 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1163 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1161 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1141 | `eslint src test && mocha --compilers babel-register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1141 | `standard && mocha -b` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1141 | `eslint src test && mocha --compilers babel-register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1141 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1137 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1136 | `mocha test/*` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1130 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1122 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1117 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1116 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1115 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1113 | `mocha --recursive --bail --reporter spec test` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1109 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1096 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1093 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1089 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1086 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1079 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1067 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1064 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1060 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1043 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1041 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1038 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1033 | `./node_modules/.bin/mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1030 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1029 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1028 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1012 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1010 | `mocha -R list` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1029 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1028 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1012 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1010 | `mocha -R list` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 1001 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 1001 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 994 | `mocha "client.test" --compilers js:babel-register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 988 | `mocha -t 600000 --exit` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 988 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 987 | `mocha tests` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 985 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 984 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 982 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 982 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 978 | `./node_modules/.bin/mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 977 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 969 | `standard && standard ./bin/* && mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 967 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 965 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 957 | `istanbul cover -- _mocha --reporter spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 956 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 951 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 951 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 944 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 937 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 937 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 879 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 874 | `istanbul cover _mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 874 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 873 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 873 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 871 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 869 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 869 | `mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 869 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 825 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 823 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 820 | `mocha index.test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 815 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 811 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 803 | `nyc mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [koajs/static](https://github.com/koajs/static) | 792 | `mocha --harmony --reporter spec --exit` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 788 | `npm run lint&&mocha tests/*.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 781 | `mocha 'test/**/*.tests.js'` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 840 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 839 | `mocha test/mocha.js test/crc/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 838 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 832 | `_mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 832 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 827 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 822 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 820 | `mocha index.test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 819 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 820 | `mocha index.test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 819 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 811 | `mocha test` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 808 | `jenkins-mocha ./tests/*.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 