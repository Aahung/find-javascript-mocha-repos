# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:44 03/08/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [expressjs/express](https://github.com/expressjs/express) | 42753 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42409 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30978 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25975 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25537 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25303 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21832 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20298 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18811 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18302 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18137 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17895 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15572 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15199 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14787 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14135 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13897 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13469 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13082 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12951 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12881 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12763 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12710 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12463 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12378 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11751 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11527 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11337 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11045 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 11004 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10771 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10753 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10492 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10012 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9891 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9752 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9646 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9566 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9491 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9397 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9293 | `mocha --opts mocha.opts` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9021 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9016 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9011 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8728 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8649 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8597 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8559 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8507 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8355 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8297 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8296 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8213 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8145 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8103 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8098 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8068 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7968 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7687 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7664 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [almende/vis](https://github.com/almende/vis) | 7663 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7646 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7627 | `npm run build && istanbul cover _mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7615 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7347 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7162 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7159 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7131 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7049 | `mocha test/test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5760 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5712 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5629 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5529 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5487 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5476 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5419 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5362 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5161 | `mocha --recursive` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5128 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5077 | `nyc mocha --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 5986 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5966 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5929 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5928 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5833 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5791 | `npm run lint && mocha tests/**/*.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5760 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5712 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5629 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5529 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5487 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5476 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5419 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5077 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5049 | `nyc mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5005 | `NODE_ENV=test mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5002 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4977 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4932 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4915 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4885 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4884 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4868 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4794 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4763 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4700 | `mocha -R spec src` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4885 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4884 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4868 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4794 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4763 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4700 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4591 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4573 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4518 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4508 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4502 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4488 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4461 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4417 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4390 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4272 | `npm run mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4267 | `npm run build && cd test && mocha . --reporter dot` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4261 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4248 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4191 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4165 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4159 | `mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4149 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4143 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4101 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4071 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4021 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3982 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3946 | `mocha && tsc -p ./test/types` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3938 | `export TESTING=true; mocha --reporter list` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3890 | `eslint . && mocha -t 5000` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3839 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3835 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3834 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3811 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3754 | `mocha test/* --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3690 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3682 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3473 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3455 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3449 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3393 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3392 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3358 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3301 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3290 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3275 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3455 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3449 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3442 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3433 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3431 | `mocha -R landing test/index --exit` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3358 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3301 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3278 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3275 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2837 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2833 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2795 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2771 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2768 | `xo && mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2749 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2745 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2725 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2716 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2685 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2640 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2992 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2984 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2982 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2945 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2945 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2926 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2920 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2877 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2837 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2833 | `mocha "./test/**/*-test.js"` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2605 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2601 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2597 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2586 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2570 | `mocha test` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2559 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2540 | `mocha test/index.js --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2536 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2528 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2510 | `nyc --require babel-register npm run _mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2477 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2464 | `mocha -R spec test/*.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2454 | `mocha --no-colors --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2614 | `TEST=all mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2605 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2601 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2597 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2595 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2592 | `mocha test/src/**/*.unit.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2586 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2570 | `mocha test` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2559 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2540 | `mocha test/index.js --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2536 | `mocha --reporter=spec test/*-test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2528 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2510 | `nyc --require babel-register npm run _mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2500 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2477 | `mocha -R spec` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1944 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1939 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1918 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1911 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1893 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1860 | `mocha ./test/test*.js --reporter spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1849 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1836 | `mocha test/setup.js test/spec/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2165 | `mocha test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2163 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2162 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2162 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2159 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2120 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [kach/nearley](https://github.com/kach/nearley) | 2109 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2088 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2079 | `mocha && npm run lint` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2069 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2066 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2060 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2033 | `mocha --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2029 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2025 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [then/promise](https://github.com/then/promise) | 2025 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2016 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2000 | `mocha test/**/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1980 | `mocha --require ./test/common --growl test/expect.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1974 | `nyc mocha --timeout=20000 test.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1972 | `bmocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1944 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1939 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1936 | `mocha test -u bdd -R spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1918 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1911 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1893 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1866 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1864 | `npm run lint && npm run mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1860 | `mocha ./test/test*.js --reporter spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1825 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1824 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1816 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1802 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1790 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1782 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1776 | `npm run lint && mocha && npm run typescript` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1764 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1762 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1759 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1758 | `mocha test/*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1757 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1751 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1747 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1641 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1641 | `mocha --recursive` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1631 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1610 | `mocha tests/test-*` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1589 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1564 | `npm run lint && npm run mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1554 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1695 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1692 | `mocha && size-limit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1687 | `NODE_ENV=test mocha tests/*.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1673 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1641 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1641 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1640 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1635 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1631 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1630 | `mocha test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1627 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1619 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1589 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1564 | `npm run lint && npm run mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1562 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1558 | `node_modules/.bin/mocha --recursive` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1554 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1547 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1547 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1545 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1539 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1536 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1534 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1534 | `mocha --recursive test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1533 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1496 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1491 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1490 | `mocha --opts test/opts/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1458 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1451 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1443 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1442 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1376 | `npm run lint && mocha --require @babel/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1374 | `cross-env NODE_ENV=test nyc mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1373 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1353 | `mocha tests/` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1352 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1349 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1347 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1337 | `mocha --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1337 | `mocha test/*.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1336 | `mocha --timeout 30000 --recursive ./tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1335 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1333 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1331 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1329 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1323 | `mocha-phantomjs tests/index.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1303 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1302 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1301 | `istanbul test _mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1294 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1280 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1275 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1254 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1451 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1448 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1443 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1442 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1438 | `webpack && npm run lint && npm run mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1425 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1425 | `npm run mocha:istanbul` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1423 | `mocha --recursive test/bin` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1421 | `istanbul cover _mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1421 | `mocha --check-leaks --reporter spec --bail test/` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1418 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1406 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1402 | `mocha --recursive` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1397 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1396 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1392 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1389 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1387 | `./node_modules/.bin/mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1376 | `npm run lint && mocha --require @babel/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1374 | `cross-env NODE_ENV=test nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1358 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1353 | `mocha tests/` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1352 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1349 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1349 | `mocha --timeout 60000 test/` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1348 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1347 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1345 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1339 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1337 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1337 | `mocha --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1337 | `mocha test/*.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1336 | `mocha --timeout 30000 --recursive ./tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1335 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1333 | `mocha src/test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1333 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1331 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1329 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1323 | `mocha-phantomjs tests/index.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1303 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1302 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1298 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1289 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1264 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1254 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1251 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1232 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1221 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1213 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1211 | `mocha test` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1199 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1195 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1180 | `mocha $(find test -name '*.test.js') --exit` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1179 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1237 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1232 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1222 | `mocha --recursive -r tests/setup tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1221 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1215 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1213 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1212 | `mocha --reporter spec test --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1211 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1180 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1179 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1175 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1163 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1161 | `istanbul cover _mocha test/*.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1161 | `npm run convertto:es5 && npm run mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1160 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1156 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1139 | `standard && mocha -b` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1134 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1134 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1133 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1112 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1111 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1104 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1102 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 779 | `npm run-script jshint && npm run-script mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 777 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 777 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 775 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 773 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 770 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 770 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 770 | `mocha 'test/**/*.tests.js'` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 769 | `mocha --ui tdd --require ./test/__setup` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 769 | `./bin/selenium-standalone install && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 765 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 763 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [electron/apps](https://github.com/electron/apps) | 756 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 752 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 746 | `mocha test.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1013 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 984 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 982 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 982 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 981 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 977 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 984 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 983 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 982 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 981 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 977 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 969 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 969 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 969 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 966 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 965 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 963 | `standard && standard ./bin/* && mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 954 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 948 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 945 | `istanbul cover -- _mocha --reporter spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 944 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 936 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 934 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 928 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 925 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 924 | `mocha -t 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 922 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 914 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 896 | `mocha --timeout 200000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 895 | `mocha --harmony --full-trace --check-leaks` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 893 | `npm run lint && mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 889 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 887 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 879 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 875 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 872 | `istanbul cover _mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 872 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 867 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 867 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 896 | `mocha --timeout 200000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 895 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 893 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 893 | `npm run lint && mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 889 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 887 | `mocha --reporter list` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 887 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 879 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 875 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 839 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 839 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 839 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 834 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 833 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 833 | `_mocha` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 832 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 828 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 823 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 821 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 817 | `mocha index.test.js` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 752 | `npm run test-mocha && npm run test-karma` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 751 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 748 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 746 | `mocha test.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 744 | `mocha --compilers js:babel-core/register` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 743 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 740 | `mocha $(find test -name '*.test.js')` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 739 | `mocha ./test/test.js --timeout 1000000` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 787 | `nyc mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 783 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 779 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 775 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [susam/texme](https://github.com/susam/texme) | 771 | `standard && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 813 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 811 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 810 | `eslint . && mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 805 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 805 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 803 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 799 | `nyc mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 799 | `nyc mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 798 | `mocha tests --timeout 10000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 794 | `mocha --recursive -s 15 test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 787 | `nyc mocha` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 714 | `mocha test/test.js` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 708 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 706 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 703 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 701 | `./node_modules/.bin/mocha` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 701 | `npm -s run mocha && npm run -s lint` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 696 | `_mocha -u bdd --colors test/` | 