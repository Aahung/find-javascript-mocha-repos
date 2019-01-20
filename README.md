# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:13 01/20/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44930 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41990 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41979 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30821 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25551 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25153 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24975 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21325 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20067 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18406 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17962 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17781 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17176 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15168 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14879 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14677 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13910 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13620 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12994 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12957 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12752 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12740 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12399 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12357 | `mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12341 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12251 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11454 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11109 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11053 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10855 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9724 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9697 | `mocha tests/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9690 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9495 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9418 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9371 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9295 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8881 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8830 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8682 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8662 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8570 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8555 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8447 | `grunt clean:test && mocha --exit` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8682 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8662 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8570 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8555 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8447 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8343 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8247 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8143 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8047 | `npm run eslint && npm run mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8041 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8005 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7904 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7849 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7843 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7761 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7587 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7586 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7504 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7460 | `mocha; jshint *.js lib` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7458 | `mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7436 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7420 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7138 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7107 | `mocha $HARMONY_OPTS` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7073 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6995 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6817 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6810 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6547 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6384 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6262 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6252 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6200 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6192 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6192 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6105 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6083 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6073 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5951 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5932 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5881 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5736 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5683 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5679 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5679 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5610 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5525 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5474 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5360 | `mocha -r esm` | 
| [teambit/bit](https://github.com/teambit/bit) | 5358 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5349 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5329 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5247 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5122 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5118 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5029 | `mocha --recursive` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4987 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4944 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4915 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4915 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4889 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4882 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4878 | `./node_modules/.bin/mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4853 | `npm run lint && npm run mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4851 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4840 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4826 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4795 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4745 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4592 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4584 | `mocha ./test/runner.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4553 | `mocha -R spec src` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4538 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4477 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4419 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4371 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4357 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4355 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4331 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4301 | `NODE_ENV=test mocha --exit` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4296 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4266 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4233 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4197 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4114 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4088 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4084 | `mocha --require should --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3970 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3928 | `export TESTING=true; mocha --reporter list` | 
| [expressjs/session](https://github.com/expressjs/session) | 3959 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3928 | `export TESTING=true; mocha --reporter list` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 3916 | `npm run build && cd test && mocha . --reporter dot` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3912 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3875 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3859 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3830 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3808 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3763 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3726 | `mocha test/* --reporter spec` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3721 | `mocha && tsc -p ./test/types` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3710 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3665 | `eslint . && mocha -t 5000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3656 | `node_modules/.bin/mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3654 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3489 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3436 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3401 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3348 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3339 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3313 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3289 | `mocha test/index.js && npm run demo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3284 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3436 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3421 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3406 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3401 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3372 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3348 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3339 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3313 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3289 | `mocha test/index.js && npm run demo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3284 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3246 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3217 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3246 | `mocha test/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3217 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3217 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3208 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3198 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3182 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3167 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3167 | `mocha --require should --reporter spec` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3149 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3145 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3129 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3088 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3079 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3060 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2977 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2976 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2974 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2960 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2958 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2955 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2943 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2916 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2916 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [github-tools/github](https://github.com/github-tools/github) | 2901 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2887 | `mocha -R spec spec spec/reporters` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2882 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2864 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2844 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2814 | `mocha --reporter dot` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2798 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2864 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2844 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2814 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2814 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2798 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2768 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2764 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2756 | `xo && mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2748 | `mocha "./test/**/*-test.js"` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2748 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2740 | `mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2727 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2274 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 2257 | `npm run lint && npm run mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2244 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2236 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2217 | `npm run lint && mocha tests/**/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2205 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2184 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2183 | `mocha test/runner.js --reporter spec` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2174 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2152 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2142 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2138 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2128 | `mocha --compilers js:babel-register` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2125 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2217 | `npm run lint && mocha tests/**/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2205 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2194 | `mocha && eslint *.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2183 | `mocha test/runner.js --reporter spec` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2174 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2171 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2152 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2146 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2130 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2125 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2274 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 2257 | `npm run lint && npm run mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2236 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2218 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2217 | `npm run lint && mocha tests/**/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2205 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2194 | `mocha && eslint *.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2184 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2183 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2180 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2174 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2171 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2152 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2142 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2138 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2128 | `mocha --compilers js:babel-register` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2125 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2081 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2050 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2050 | `mocha test/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2046 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2038 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2046 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2038 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2037 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2029 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2024 | `mocha tests --require @babel/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2018 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2015 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2012 | `mocha && npm run lint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2002 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1986 | `mocha test` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1978 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1966 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1960 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1966 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1960 | `mocha --bail --reporter spec --check-leaks test/` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1950 | `mocha test/**/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1947 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1946 | `mocha --reporter spec && npm run test-typescript` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1945 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1943 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1925 | `npm run lint && mocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1924 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1908 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1897 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1892 | `mocha test -u bdd -R spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1775 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1758 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1753 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1745 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1736 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1736 | `mocha test/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1710 | `mocha test/test-*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1706 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1705 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1703 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1703 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1694 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1691 | `mocha --check-leaks --reporter spec --bail` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1682 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1673 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1670 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1662 | `mocha spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1648 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1631 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1628 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1626 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1620 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1691 | `mocha --check-leaks --reporter spec --bail` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1682 | `mocha && size-limit` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1680 | `mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1673 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1670 | `mocha ./test/test*.js --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1670 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1662 | `mocha spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1649 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1648 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1638 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1631 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1422 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1405 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [electron/devtron](https://github.com/electron/devtron) | 1404 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1404 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1393 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1392 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1386 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1384 | `./node_modules/mocha/bin/mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1374 | `mocha --check-leaks --reporter spec --bail test/` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1360 | `NODE_PATH=. mocha **/*.spec.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1353 | `mocha --compilers js:babel-core/register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1546 | `mocha tests/test-*` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1541 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1539 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1536 | `mocha --check-leaks --require @babel/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1535 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1522 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1521 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1510 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1508 | `npm run lint && mocha && karma start --single-run` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1507 | `npm run lint && npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1505 | `mocha test/**/*.spec.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1503 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1503 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1496 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1494 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1492 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1489 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1508 | `npm run lint && mocha && karma start --single-run` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1507 | `npm run lint && npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1505 | `mocha test/**/*.spec.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1503 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1503 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1496 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1494 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1492 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1489 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1468 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1467 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1462 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1461 | `standard && istanbul cover _mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1456 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1451 | `mocha --opts test/opts/mocha.opts` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1510 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1508 | `npm run lint && mocha && karma start --single-run` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1507 | `npm run lint && npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1505 | `mocha test/**/*.spec.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1503 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1503 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1496 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1494 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1492 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1489 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1468 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1467 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1462 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1461 | `standard && istanbul cover _mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1456 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1451 | `npm run prepublishOnly && mocha test/test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1445 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1445 | `mocha --recursive test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1426 | `mocha test --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1421 | `npm run build && mocha -r should` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1410 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1406 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1404 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1404 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1406 | `istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1405 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [electron/devtron](https://github.com/electron/devtron) | 1404 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1401 | `mocha --recursive test/bin` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1400 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1393 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1392 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1386 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1374 | `mocha --check-leaks --reporter spec --bail test/` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1372 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1360 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1312 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1299 | `npm run lint && npm run mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1297 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1290 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1287 | `mocha --timeout 30000 --recursive ./tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1286 | `mocha --timeout 20000` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1286 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1266 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1257 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1249 | `mocha --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1266 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1258 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1255 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1249 | `mocha --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1238 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1237 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1236 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1223 | `node ./node_modules/mocha/bin/mocha tests` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1222 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1220 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1287 | `mocha --timeout 30000 --recursive ./tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1286 | `mocha --timeout 20000` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1286 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1266 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1258 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1257 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1255 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1249 | `mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1197 | `mocha --recursive -r tests/setup tests` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1182 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1179 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1175 | `mocha --reporter spec --bail --check-leaks test/` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1168 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1166 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1166 | `mocha --reporter spec --bail --check-leaks test/` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1168 | `mocha $(find test -name '*.test.js') --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1167 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1166 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1166 | `mocha --reporter spec --bail --check-leaks test/` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1164 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1164 | `npm-run-all test:jest test:server:mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1164 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1155 | `istanbul cover _mocha test/*.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1146 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1141 | `webpack && mocha test/unit` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1134 | `mocha --reporter spec test --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1133 | `mocha test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1117 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1115 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1114 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1098 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1097 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1096 | `eslint src test && mocha --compilers babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1087 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 902 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 901 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 893 | `mocha --timeout 200000` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 885 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 880 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 871 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 1066 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1062 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1062 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1052 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1048 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1044 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1042 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1040 | `npm run lint && npm run mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1029 | `mocha --reporter spec --timeout 3000` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1019 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1019 | `mocha test/*.test.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1013 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1011 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1005 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1001 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 999 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 997 | `mocha spec/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 994 | `npm run lint && mocha -R spec` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 994 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 992 | `./node_modules/.bin/mocha -R spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 990 | `mocha --compilers js:babel-register test/*.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 981 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 981 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 975 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 971 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 968 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 965 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 963 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 960 | `mocha tests` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 960 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 959 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 958 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 957 | `mocha -t 600000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 955 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 945 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 945 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 944 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 944 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 940 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 938 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 930 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 927 | `istanbul cover -- _mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 856 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 854 | `mocha --reporter spec --bail --check-leaks test/` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 848 | `mocha --opts mocha.opts` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 847 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 845 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 844 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 837 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 833 | `mocha test` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 828 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 845 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 844 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 837 | `mocha -r babel-register --check-leaks test/index.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 834 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 833 | `mocha test` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 828 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 828 | `npm run lint && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 827 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 825 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 819 | `npm run mocha-test test/integration` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 819 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 818 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 816 | `mocha --colors --reporter spec test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 814 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 828 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 828 | `npm run lint && mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 827 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 825 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 819 | `npm run mocha-test test/integration` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 819 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 818 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 816 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 814 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 811 | `_mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 810 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 850 | `mocha --harmony tests/**` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 848 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 848 | `mocha --opts mocha.opts` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 847 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 846 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 846 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 845 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 843 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 839 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [developit/decko](https://github.com/developit/decko) | 837 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 837 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 836 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 834 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 833 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 830 | `nyc mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 828 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 828 | `npm run lint && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 827 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 825 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 819 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 819 | `npm run mocha-test test/integration` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 819 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 818 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 816 | `mocha --colors --reporter spec test.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 784 | `nyc mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 781 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 780 | `mocha tests --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 774 | `mocha -R spec src/**/*_test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 770 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 769 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 769 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 768 | `eslint . && mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 767 | `mocha test` | 
| [koajs/static](https://github.com/koajs/static) | 766 | `mocha --harmony --reporter spec --exit` | 