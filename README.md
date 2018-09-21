# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:04 09/21/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43614 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41348 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40256 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30324 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26634 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24647 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24566 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23620 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20133 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19215 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17367 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17010 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16947 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15483 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14396 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14163 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13842 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13346 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12955 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12732 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12433 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12251 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12130 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11664 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11472 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11414 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10681 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10370 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10305 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10233 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10132 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10087 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9080 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8890 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8888 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8842 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8712 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8465 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8359 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8240 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8228 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8107 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8054 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7815 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7774 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8240 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8228 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8107 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8054 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7942 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7815 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7774 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7564 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7467 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7441 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7390 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7371 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7367 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7219 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7181 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7120 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7115 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6961 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6876 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6790 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6762 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6626 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6562 | `npm run jshint && mocha test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6540 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6334 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6320 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6267 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6052 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6048 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6004 | `mocha tests/node.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5955 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5940 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5879 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5788 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5771 | `mocha && eslint lib/**` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5769 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5765 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5638 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5458 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5446 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5440 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5421 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5207 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5183 | `mocha src/**/*Tests.js --harmony` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5177 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5148 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5106 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5014 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4878 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4868 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4807 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4779 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4771 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4754 | `mocha -R spec 'tests/app'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4740 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4703 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4678 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4577 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4566 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4537 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4523 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4514 | `nyc mocha --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4457 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4449 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4356 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4347 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4232 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4230 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4169 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4133 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4116 | `mocha --timeout=15000 tests/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4116 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4063 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4062 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4054 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4052 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4013 | `mocha --require should --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4011 | `nyc --require ./test/helpers/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4010 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3995 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3946 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3941 | `mocha --check-leaks --reporter spec --bail` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3904 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3876 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3701 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3694 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [primus/primus](https://github.com/primus/primus) | 3689 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3671 | `npm run jshint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3620 | `NODE_ENV=test mocha --exit` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3617 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3584 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3572 | `node_modules/.bin/mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3565 | `NODE_ENV=test mocha test/**/*.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3556 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3552 | `mocha --reporter spec --timeout 3000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3542 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3507 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3453 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3446 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3343 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3326 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3305 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3272 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3272 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3260 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3235 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3190 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3169 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3167 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3155 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3155 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3137 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3135 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3122 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3111 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3109 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3108 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3101 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3084 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3077 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3058 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2913 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2908 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2894 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2885 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2880 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2874 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2869 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2844 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2822 | `mocha -R spec spec spec/reporters` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2822 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2811 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2764 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2742 | `mocha test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2869 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2844 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2822 | `mocha -R spec spec spec/reporters` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2822 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2815 | `mocha test-node` | 
| [mde/ejs](https://github.com/mde/ejs) | 2811 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2803 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2797 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2764 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2742 | `mocha test.js` | 
| [css/csso](https://github.com/css/csso) | 2737 | `mocha --reporter dot` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2735 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2729 | `xo && mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2727 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2615 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2613 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2613 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2597 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2585 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2576 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2560 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2528 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2500 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2499 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2494 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2491 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2478 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2475 | `mocha test/src/**/*.unit.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2473 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2467 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2454 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2528 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2500 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2499 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2494 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2491 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2478 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2475 | `mocha test/src/**/*.unit.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2473 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2467 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2454 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2419 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2418 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2401 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2292 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2286 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2284 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2239 | `mocha test test/unit/**/*_test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2238 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2230 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2224 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2208 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1407 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1405 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1385 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1377 | `mocha tests/test-*` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1370 | `mocha --opts test/opts/mocha.opts` | 
| [electron/devtron](https://github.com/electron/devtron) | 1369 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1362 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1348 | `mocha --reporter dot` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1342 | `mocha ./test/test*.js --reporter spec` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1335 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1330 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1321 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1314 | `npm run lint && npm run mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1310 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1304 | `mocha spec/exec.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1298 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1297 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1294 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1288 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1287 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1285 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1281 | `mocha --recursive test/bin` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1279 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1278 | `mocha --check-leaks --reporter spec --bail test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1273 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1269 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1269 | `mocha test/*.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1267 | `npm run prepublishOnly && mocha test/test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1262 | `mocha --recursive test` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1262 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1251 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1250 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1248 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1247 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1244 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1240 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1237 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1237 | `npm run lint && npm run mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1236 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1233 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1212 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1211 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1209 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1202 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1202 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1199 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1197 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1185 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1181 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1165 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1163 | `npm run mocha:istanbul` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1156 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1156 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1155 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1141 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1136 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1134 | `istanbul cover _mocha test/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1132 | `mocha --timeout 20000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1129 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1129 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1122 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1091 | `webpack && mocha test/unit` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1085 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1084 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1083 | `mocha --timeout 30000 --recursive ./tests` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1076 | `mocha --reporter spec --bail --check-leaks test/` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1075 | `mocha --recursive --bail --reporter spec test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1067 | `mocha test --compilers js:babel-core/register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1067 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1065 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1063 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 954 | `mocha "client.test" --compilers js:babel-register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 953 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 950 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 943 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 931 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 927 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 926 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 920 | `mocha test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 916 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1078 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1076 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1075 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1075 | `mocha --recursive --bail --reporter spec test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1067 | `mocha test --compilers js:babel-core/register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1067 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1065 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1063 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1054 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1051 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1051 | `npm-run-all test:jest test:server:mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1049 | `mocha && standard` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 994 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 991 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 990 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 983 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 981 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 975 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 964 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 963 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 963 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1008 | `mocha --recursive -r tests/setup tests` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1005 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 994 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 991 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 990 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 983 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 981 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 981 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 920 | `mocha test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 916 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 912 | `mocha -t 600000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 901 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 899 | `./node_modules/.bin/mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 898 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 897 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 897 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 897 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 895 | `nyc mocha specs` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 893 | `nyc --check-coverage mocha test/*.test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 893 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 893 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 889 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 888 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 882 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 882 | `mocha --recursive ./test/*_spec.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 880 | `istanbul cover -- _mocha --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 877 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 877 | `standard && standard ./bin/* && mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 876 | `npm run lint && npm run mocha:no-functional` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 876 | `mocha test --compilers js:babel-register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 876 | `mocha --reporter list` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 875 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 875 | `mocha -t 5000` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 873 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 873 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 854 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 848 | `mocha --reporter spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 846 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 844 | `mocha test/index.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 841 | `npm run lint && mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 841 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 840 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 839 | `mocha test` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 839 | `mocha --exit --use_strict src/*.test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 837 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 836 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 829 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 817 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 816 | `./node_modules/.bin/mocha test/**/*` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 815 | `mocha tests/*.test.js --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 813 | `mocha --harmony --full-trace --check-leaks` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 813 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 812 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 811 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 810 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 810 | `npm run build && istanbul test _mocha test/test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 807 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 806 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 802 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 801 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 813 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 812 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 811 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 810 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 810 | `npm run build && istanbul test _mocha test/test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 807 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 806 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 802 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 801 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 798 | `mocha -u tdd` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 797 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 797 | `mocha -R spec tests/` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 797 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 796 | `mocha --colors --reporter spec test.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 796 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 795 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 789 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 788 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 787 | `mocha -r should --reporter spec test/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 786 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 783 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 783 | `xo && mocha -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 782 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 781 | `mocha test` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 779 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 777 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 777 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 775 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 745 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 744 | `babel-node node_modules/.bin/_mocha -- test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 741 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 739 | `mocha tests/*.mocha.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 733 | `npm run-script jshint && npm run-script mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 732 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 730 | `nyc mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 730 | `mocha --harmony tests/**` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 730 | `mocha --reporter spec build/test/index.js` | 
| [koajs/static](https://github.com/koajs/static) | 718 | `mocha --harmony --reporter spec --exit` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 715 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 714 | `mocha ./test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 711 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 709 | `mocha ./test/test.js --timeout 1000000` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 708 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 706 | `mocha $(find test -name '*.test.js')` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 703 | `npm run test-mocha && npm run test-karma` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 745 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 744 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 743 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 741 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 739 | `mocha tests/*.mocha.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 737 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 735 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 734 | `npm run bundle && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 733 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 722 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 719 | `npm run lint && mocha` | 
| [koajs/static](https://github.com/koajs/static) | 718 | `mocha --harmony --reporter spec --exit` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 715 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 714 | `mocha ./test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 711 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 709 | `mocha ./test/test.js --timeout 1000000` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 709 | `mocha ./test/test.js --timeout 1000000` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 708 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 706 | `mocha $(find test -name '*.test.js')` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 703 | `npm run test-mocha && npm run test-karma` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 697 | `jenkins-mocha ./tests/*.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 696 | `mocha --reporter spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 693 | `mocha --compilers js:babel-core/register` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 692 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 688 | `mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 687 | `mocha --reporter spec --bail --check-leaks test/` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 686 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 685 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 684 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require babel-register` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 682 | `mocha --reporter spec test/` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 682 | `npm run lint && mocha test` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 677 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 677 | `mocha` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 676 | `mocha --reporter spec` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 674 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 673 | `mocha -b -R spec test/*` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 673 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 672 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 672 | `mocha --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 670 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 669 | `mocha -R spec` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 666 | `mocha --compilers js:babel-register` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 666 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 666 | `mocha --compilers js:babel-register` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 666 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 662 | `./node_modules/.bin/mocha` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 662 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 659 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 639 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 638 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 638 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 638 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [formio/formio](https://github.com/formio/formio) | 634 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 632 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 631 | `eslint . && mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 630 | `istanbul cover _mocha` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 629 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 627 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 627 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 626 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 625 | `mocha test` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 625 | `mocha --ui bdd --reporter spec` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 625 | `mocha --ui bdd --reporter spec` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 623 | `node_modules/.bin/mocha test` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 622 | `mocha -R spec spec/unit spec/integration` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 620 | `mocha ./test --bail` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 620 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 619 | `mocha --reporter spec` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 618 | `mocha` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 618 | `mocha` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 617 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 615 | `npm -s run mocha && npm run -s lint` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 613 | `nyc mocha test.js` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 613 | `npm run lint && npm run mocha` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 613 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 626 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 625 | `mocha test` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 625 | `mocha --ui bdd --reporter spec` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 623 | `node_modules/.bin/mocha test` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 623 | `mocha 'test/**/*.tests.js'` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 622 | `mocha -R spec spec/unit spec/integration` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 620 | `mocha ./test --bail` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 620 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 619 | `mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 619 | `mocha --reporter spec` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 618 | `mocha` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 618 | `mocha` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 617 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 620 | `mocha ./test --bail` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 620 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 619 | `mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 619 | `mocha --reporter spec` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 618 | `mocha` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 618 | `mocha` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 617 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 615 | `npm -s run mocha && npm run -s lint` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 613 | `nyc mocha test.js` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 613 | `npm run lint && npm run mocha` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 613 | `mocha` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 612 | `gulp build && mocha test.js` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 611 | `nyc mocha` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 611 | `./node_modules/mocha/bin/mocha` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 611 | `mocha --compilers js:babel/register --recursive` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 609 | `mocha --check-leaks --reporter spec --bail test/` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 609 | `mocha` | 
| [VictorBjelkholm/autochecker](https://github.com/VictorBjelkholm/autochecker) | 608 | `mocha` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 608 | `node_modules/.bin/mocha` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 605 | `gulp mocha` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 604 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 604 | `mocha` | 
| [nexus-js/ui](https://github.com/nexus-js/ui) | 603 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 602 | `mocha && jshint .` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 602 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 601 | `mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 595 | `nyc mocha && nyc report -r html mocha` | 
| [JustClear/blurify](https://github.com/JustClear/blurify) | 594 | `mocha test/index.js` | 
| [times/cardkit](https://github.com/times/cardkit) | 594 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 594 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 593 | `mocha test/index.js` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 593 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 593 | `mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 591 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 591 | `mocha --ui bdd --reporter spec test/` | 
| [teropa/redux-voting-server](https://github.com/teropa/redux-voting-server) | 591 | `mocha --compilers js:babel-core/register  --require ./test/test_helper.js  --recursive` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 589 | `mocha --compilers js:babel-register` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 588 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 588 | `mocha --compilers js:./babel-register` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 587 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 587 | `mocha test/test.js --reporter spec` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 585 | `istanbul cover _mocha && eslint .` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 584 | `tav --ci && mocha test/index.js` | 