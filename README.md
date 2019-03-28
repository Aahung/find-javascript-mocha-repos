# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:13 03/28/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45720 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 43058 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42520 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31026 | `nyc mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26157 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25820 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25370 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 22058 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20417 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15786 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15330 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14822 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14218 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13120 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 13063 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12841 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12514 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12391 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13120 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 13063 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12931 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12903 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12841 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12514 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12391 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11884 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11734 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11488 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11147 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 11146 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10938 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10824 | `mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11147 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 11146 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10938 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10824 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10549 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10162 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9951 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9808 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9739 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9680 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9524 | `mocha -b -r esm` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9451 | `mocha --opts mocha.opts` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9430 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9222 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9172 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9082 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8766 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8703 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8688 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8608 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8531 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8503 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8359 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8330 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8289 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8244 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8205 | `npm run eslint && npm run mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8169 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8134 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 8016 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7604 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7471 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7326 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7192 | `npm run jshint && mocha test/` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7180 | `mocha $HARMONY_OPTS` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7150 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6678 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6678 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6516 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6457 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6401 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6373 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6351 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6316 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6287 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 6282 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6267 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6180 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5257 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5200 | `npm run lint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5191 | `NODE_ENV=test mocha --exit` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5164 | `nyc mocha --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5158 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5125 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5121 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5023 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5011 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4939 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4929 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4911 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4895 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4890 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4890 | `mocha --recursive --colors` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5445 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5257 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5200 | `npm run lint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5191 | `NODE_ENV=test mocha --exit` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5164 | `nyc mocha --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5158 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5125 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5121 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5023 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5011 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4939 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4929 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4911 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4895 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4890 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4890 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4770 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4769 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4728 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4613 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4608 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4602 | `npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4595 | `mocha ./test/runner.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4568 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4540 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4527 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4497 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4419 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4400 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4314 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4177 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4164 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4110 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4086 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4033 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 4018 | `mocha && tsc -p ./test/types` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3859 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3853 | `npm run build && mocha test/*.test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3796 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3778 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3647 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3643 | `nyc mocha && tsc` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3627 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3624 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3609 | `mocha tests/javascript` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3592 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3585 | `mocha -R landing test/index --exit` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3565 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3558 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3505 | `node_modules/.bin/mocha test/lib/` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3498 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3476 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3471 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3464 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3439 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3425 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3328 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3305 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3304 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3249 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3213 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3196 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3187 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3180 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3104 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3083 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3076 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2927 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2925 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2909 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2812 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2790 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2776 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2714 | `mocha --timeout 100000` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2670 | `TEST=all mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2663 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2661 | `mocha-phantomjs ./test/index.html` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2649 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2624 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3034 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 3001 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2999 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2993 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2932 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2927 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2925 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2909 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2854 | `istanbul cover _mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2812 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2854 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2850 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2812 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2798 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2790 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2776 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2775 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2754 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2752 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2719 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2714 | `mocha --timeout 100000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2969 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2932 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2927 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2925 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2909 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2868 | `mocha "./test/**/*-test.js"` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2854 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2850 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2812 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2463 | `npm run build && mocha --require @babel/register` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2462 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2458 | `mocha --no-colors --reporter spec` | 
| [pahen/madge](https://github.com/pahen/madge) | 2436 | `npm run lint && npm run mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2430 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2364 | `mocha test/**/*.coffee` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2355 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2339 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2326 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2578 | `mocha test` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2577 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2572 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2571 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2568 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2556 | `nyc --require babel-register npm run _mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2540 | `mocha --reporter=spec test/*-test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2539 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2536 | `export TESTING=true; mocha --reporter list` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2487 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2482 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2463 | `npm run build && mocha --require @babel/register` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2458 | `mocha --no-colors --reporter spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2355 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2343 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2339 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2326 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2305 | `mocha test/test-*.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2301 | `standard && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2297 | `./node_modules/.bin/mocha && npm run jshint` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2296 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2277 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2245 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2241 | `mocha --compilers js:babel-register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2233 | `mocha test` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2232 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2222 | `mocha test/runner.js --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2217 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2194 | `cross-env BABEL_ENV=test mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2190 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2177 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2177 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2174 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2167 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2153 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2132 | `mocha tests --require @babel/register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2132 | `mocha test/*.test.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2113 | `mocha --recursive` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2082 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2075 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2069 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2066 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2057 | `mocha --reporter spec --timeout 5000` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2043 | `nyc mocha --timeout=20000 test.js` | 
| [then/promise](https://github.com/then/promise) | 2037 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2036 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2026 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2024 | `mocha test/**/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 2008 | `mocha tests.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2006 | `mocha --reporter spec && npm run test-typescript` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1990 | `mocha --require ./test/common --growl test/expect.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1983 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1979 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1978 | `npm run lint && mocha --reporter spec test/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1965 | `mocha test -u bdd -R spec` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1965 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1964 | `mocha --reporter spec --grep .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1959 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1956 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1954 | `mocha test` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1729 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1671 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1658 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1656 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1655 | `mocha test/unit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1649 | `mocha --reporter spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1641 | `mocha tests/test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1638 | `mocha tests/test-*` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1600 | `npm run lint && npm run mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1595 | `nyc mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1744 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1741 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1740 | `mocha test --timeout 600000` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1730 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1729 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1727 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1716 | `NODE_ENV=test mocha tests/*.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1698 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1698 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1696 | `npm run jshint && mocha --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1692 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1688 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1673 | `mocha spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1671 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1698 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1692 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1673 | `mocha spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1671 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1663 | `mocha -R spec ./test/unit/**` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1658 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1656 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1655 | `mocha test/unit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1649 | `mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1647 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1641 | `mocha tests/test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1730 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1729 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1727 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1716 | `NODE_ENV=test mocha tests/*.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1698 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1698 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1696 | `npm run jshint && mocha --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1692 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1688 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1663 | `mocha -R spec ./test/unit/**` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1658 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1656 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1655 | `mocha test/unit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1649 | `mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1647 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1641 | `mocha tests/test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1638 | `mocha tests/test-*` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1636 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1633 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1621 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [electron/devtron](https://github.com/electron/devtron) | 1433 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1432 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1430 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1422 | `mocha --compilers js:babel-core/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1418 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1412 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1410 | `mocha --recursive` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1402 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1398 | `npm run lint && mocha --require @babel/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1393 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1384 | `mocha tests/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1381 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1378 | `cross-env NODE_ENV=test nyc mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1371 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1449 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1443 | `mocha --recursive test/bin` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1433 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1432 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1430 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1430 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1422 | `mocha --compilers js:babel-core/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1418 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1412 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1410 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1402 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1398 | `npm run lint && mocha --require @babel/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1397 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1394 | `mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1393 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1384 | `mocha tests/` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1378 | `cross-env NODE_ENV=test nyc mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1371 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1362 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1362 | `mocha` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1360 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1351 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1347 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1346 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1343 | `npm run lint && npm run mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1339 | `mocha spec/exec.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1347 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1346 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1343 | `npm run lint && npm run mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1343 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1341 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1339 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1339 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1333 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1327 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1324 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1319 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1312 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1288 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1273 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1273 | `mocha test` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1261 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1249 | `mocha --reporter spec test --recursive` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1243 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1239 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1236 | `node ./node_modules/mocha/bin/mocha tests` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1233 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1213 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1213 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1210 | `mocha test/test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1199 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1174 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1172 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1167 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1166 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1164 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1149 | `eslint src test && mocha --compilers babel-register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1145 | `standard && mocha -b` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1136 | `mocha test/*` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1190 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1188 | `mocha $(find test -name '*.test.js') --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1186 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1182 | `npm run convertto:es5 && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1179 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1177 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1174 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1172 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1167 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1166 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1164 | `mocha && standard` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1061 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1055 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1044 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1042 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1036 | `mocha spec/*.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1035 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1034 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1034 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1030 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1021 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1017 | `mocha --compilers js:babel-register test/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1118 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1117 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1114 | `mocha --recursive --bail --reporter spec test` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1111 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1109 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1108 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1102 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1093 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1086 | `mocha test` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 975 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 971 | `standard && standard ./bin/* && mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 959 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 958 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 956 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 951 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1030 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1021 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1017 | `mocha --compilers js:babel-register test/*.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1011 | `mocha -R list` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 1009 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 998 | `mocha "client.test" --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 995 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 995 | `mocha tests` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 990 | `mocha -t 600000 --exit` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 989 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 986 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 984 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 982 | `npm run rollup-cjs && mocha test/test.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 980 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 976 | `nyc mocha specs` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 976 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 975 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 971 | `standard && standard ./bin/* && mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 968 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 967 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 959 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 959 | `istanbul cover -- _mocha --reporter spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 958 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 956 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 951 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 947 | `mocha test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 945 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 935 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 931 | `mocha -r should --exit test/*.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 931 | `mocha -r should --exit test/*.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 929 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 929 | `mocha -t 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 926 | `mocha test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 925 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 924 | `mocha --harmony tests/**` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 921 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 920 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 919 | `mocha spec/*.spec.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 917 | `npm run lint && npm run mocha:no-functional` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 916 | `npm run lint && mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 915 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 897 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 890 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 883 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 883 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 877 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 875 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 873 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 871 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 870 | `mocha --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 869 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 868 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 868 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 866 | `mocha test` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 863 | `nyc mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 861 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 861 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 856 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 855 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 824 | `mocha index.test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 821 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 812 | `jenkins-mocha ./tests/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 810 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 821 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 812 | `jenkins-mocha ./tests/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 810 | `mocha test` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 810 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 821 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 812 | `jenkins-mocha ./tests/*.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 810 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 753 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 751 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 748 | `mocha test.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 747 | `mocha --compilers js:babel-core/register` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 745 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 745 | `mocha $(find test -name '*.test.js')` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 742 | `npm run bundle && mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 741 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 741 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 740 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 740 | `mocha --reporter spec test/` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 740 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 739 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 738 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 