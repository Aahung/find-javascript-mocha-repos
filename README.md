# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:47 03/24/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45651 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42988 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42509 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31017 | `nyc mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26107 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25751 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25355 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 22009 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20393 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 19012 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18431 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18234 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18105 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15737 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15301 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14815 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14197 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12503 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11849 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11679 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11439 | `set NODE_ENV=test && mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10898 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10820 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10533 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10127 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9931 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9931 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9655 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9521 | `mocha -b -r esm` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9422 | `mocha --opts mocha.opts` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9419 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9172 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9141 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9059 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8760 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8696 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8674 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8601 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8528 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8475 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9141 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9059 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8760 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8696 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8674 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8601 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8528 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8475 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8324 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8316 | `mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8293 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8222 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8152 | `npm run eslint && npm run mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8142 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8124 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 8003 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7807 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7782 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7732 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7724 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7718 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7648 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7603 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7442 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7292 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7179 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7169 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7119 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6672 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6483 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6455 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6393 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6362 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6335 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6301 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6282 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6249 | `standard && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6242 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6174 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6066 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 6004 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5949 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5915 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5861 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5790 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5788 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5650 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5593 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5549 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5530 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5520 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5019 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5007 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4936 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4926 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4894 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4883 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4867 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4768 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4750 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4689 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4608 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4594 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4589 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4903 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4894 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4883 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4867 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4768 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4750 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4689 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4608 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4594 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4589 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4557 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4533 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4529 | `npm run mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4513 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4497 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4431 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4407 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4400 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4188 | `mocha --require test/babel-hook test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4178 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4171 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4153 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4108 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4108 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4069 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4024 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 4007 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3981 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3941 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3856 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3849 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3841 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3798 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3712 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3637 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3628 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3623 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3614 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3609 | `mocha tests/javascript` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3582 | `mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3565 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3549 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3545 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3513 | `mocha -R landing test/index --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3484 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3473 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3471 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3449 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3430 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3417 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3386 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3323 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3302 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3299 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3194 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3187 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3181 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3174 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3209 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3194 | `./node_modules/.bin/mocha test/test.*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3181 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3174 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3168 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3145 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3129 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3103 | `node_modules/.bin/mocha --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3086 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3086 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3075 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3073 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3069 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3052 | `mocha --require @babel/register --recursive spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3039 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3039 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3013 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 3000 | `mocha -R spec --recursive src/test` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3145 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3129 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3103 | `node_modules/.bin/mocha --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3086 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3086 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3075 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3073 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3069 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3052 | `mocha --require @babel/register --recursive spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3039 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3039 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3013 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 3000 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2994 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2991 | `mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2904 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2857 | `mocha "./test/**/*-test.js"` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2853 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2845 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2812 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2789 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2776 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2774 | `xo && mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2771 | `nyc mocha` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2768 | `cross-env TEST_BROWSER_DRIVER=chrome BABEL_ENV=coverage COVERAGE=1 COVERAGE_OUT_LCOVONLY=1 COVERAGE_APP_FOLDER=$PWD/ meteor test --once --driver-package meteortesting:mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2753 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2745 | `mocha test/unit --require mochahook` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2658 | `mocha-phantomjs ./test/index.html` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2656 | `TEST=all mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2654 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2621 | `mocha && eslint .` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2599 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2598 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2576 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2567 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2567 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2564 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2562 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2539 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2536 | `export TESTING=true; mocha --reporter list` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1776 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1771 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1769 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1749 | `./node_modules/.bin/mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1748 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1739 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1730 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1710 | `NODE_ENV=test mocha tests/*.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1697 | `mocha && size-limit` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2230 | `mocha --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2222 | `mocha test/runner.js --reporter spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2220 | `mocha test` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2217 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2194 | `cross-env BABEL_ENV=test mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2175 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2174 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2172 | `mocha --compilers js:babel-core/register __tests__` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2147 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2126 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2125 | `mocha tests --require @babel/register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2105 | `mocha && npm run lint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2067 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2056 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2033 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2029 | `nyc mocha --timeout=20000 test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2020 | `mocha test/**/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1993 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2020 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2004 | `mocha --reporter spec && npm run test-typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1993 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1986 | `mocha --require ./test/common --growl test/expect.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1981 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1977 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1975 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1962 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1961 | `mocha test -u bdd -R spec` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1960 | `mocha --reporter spec --grep .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1952 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1923 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1906 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1887 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1884 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1873 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1868 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1867 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1749 | `./node_modules/.bin/mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1748 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1741 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1740 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1726 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1710 | `NODE_ENV=test mocha tests/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1698 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1697 | `mocha && size-limit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1695 | `npm run jshint && mocha --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1689 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1695 | `npm run jshint && mocha --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1689 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1670 | `mocha spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1666 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1656 | `mocha -R spec ./test/unit/**` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1647 | `mocha --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1644 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1632 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1631 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1258 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1234 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1233 | `node ./node_modules/mocha/bin/mocha tests` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1198 | `xo && mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1171 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1165 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1163 | `webpack && mocha test/unit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1595 | `nyc mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1591 | `npm run lint && npm run mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1577 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1573 | `mocha` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1571 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1570 | `npm run lint && mocha && karma start --single-run` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1563 | `mocha --recursive test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1560 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1558 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1556 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1555 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1552 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1549 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1546 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1521 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1513 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [trufflesuite/ganache](https://github.com/trufflesuite/ganache) | 1508 | `npm run test-mocha && npm run test-jest` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1498 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1495 | `mocha --opts test/opts/mocha.opts` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1487 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1463 | `npm run mocha:istanbul` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1456 | `mocha test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1454 | `webpack && npm run lint && npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1452 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1448 | `npm run build && mocha -r should` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1438 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1437 | `mocha --check-leaks --reporter spec --bail test/` | 
| [electron/devtron](https://github.com/electron/devtron) | 1431 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1430 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1426 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1417 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1416 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1408 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1402 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1448 | `npm run build && mocha -r should` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1438 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1437 | `mocha --check-leaks --reporter spec --bail test/` | 
| [electron/devtron](https://github.com/electron/devtron) | 1431 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1430 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1426 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1417 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1416 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1408 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1402 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1400 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1395 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1392 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1389 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1384 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1367 | `mocha --timeout 20000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1362 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1361 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1355 | `mocha --timeout 60000 test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1354 | `mocha --timeout 30000 --recursive ./tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1350 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1346 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1343 | `npm run lint && npm run mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1342 | `mocha test/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1331 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1329 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1318 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1317 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1306 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1305 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1305 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1268 | `mocha test` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1207 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1188 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1185 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1171 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1163 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1188 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1185 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1171 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1163 | `mocha && standard` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1163 | `webpack && mocha test/unit` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1145 | `standard && mocha -b` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1144 | `eslint src test && mocha --compilers babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1140 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1136 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1135 | `mocha test/*` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1198 | `xo && mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1191 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1188 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1185 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1185 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1179 | `npm run convertto:es5 && npm run mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1173 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1171 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1165 | `istanbul cover _mocha test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1163 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1145 | `standard && mocha -b` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1144 | `eslint src test && mocha --compilers babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1140 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1136 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1135 | `mocha test/*` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1123 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1145 | `standard && mocha -b` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1144 | `eslint src test && mocha --compilers babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1140 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1136 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1135 | `mocha test/*` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1016 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1010 | `mocha -R list` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 1004 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 995 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 995 | `mocha "client.test" --compilers js:babel-register` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 989 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 988 | `mocha -t 600000 --exit` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 988 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 985 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1061 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1042 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1039 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1036 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1035 | `./node_modules/.bin/mocha -R spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1034 | `mocha spec/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1033 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1033 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1032 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1032 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1031 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 846 | `ts-mocha test/` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 846 | `mocha test` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 844 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 843 | `mocha test/mocha.js test/crc/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 842 | `mocha --async-only` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 838 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 835 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 823 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 820 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 819 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 811 | `mocha test` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 810 | `jenkins-mocha ./tests/*.js` | 
| [node-cron/node-cron](https://github.com/node-cron/node-cron) | 808 | `nyc --reporter=html --reporter=text mocha --recursive` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 807 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 798 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 796 | `mocha --recursive -s 15 test/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 795 | `mocha tests --timeout 10000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 785 | `mocha 'test/**/*.tests.js'` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 781 | `babel-node node_modules/.bin/_mocha -- test` | 
| [susam/texme](https://github.com/susam/texme) | 780 | `standard && mocha` | 
| [susam/texme](https://github.com/susam/texme) | 780 | `standard && mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 776 | `mocha -R spec src/**/*_test.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 774 | `./bin/selenium-standalone install && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 773 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [electron/apps](https://github.com/electron/apps) | 766 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 761 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 761 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 770 | `mocha --ui tdd --require ./test/__setup` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 767 | `mocha --reporter spec build/test/index.js` | 
| [electron/apps](https://github.com/electron/apps) | 766 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 763 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 761 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 761 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 759 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 755 | `npm run test-mocha && npm run test-karma` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 755 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 754 | `mocha tests/*.mocha.js` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 761 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 761 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 759 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 755 | `npm run test-mocha && npm run test-karma` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 755 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 754 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [formio/formio](https://github.com/formio/formio) | 751 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 748 | `mocha test.js` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 747 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 747 | `mocha --compilers js:babel-core/register` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 741 | `mocha --reporter spec` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 740 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 740 | `mocha --reporter spec test/` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 740 | `mocha` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 740 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 740 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 738 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 736 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 731 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 731 | `mocha test/test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 730 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 730 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 730 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 687 | `mocha --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 685 | `nyc --reporter=text --reporter=lcov mocha` | 
| [shime/livedown](https://github.com/shime/livedown) | 682 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 681 | `mocha --require babel-register` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 681 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 677 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 675 | `node_modules/.bin/mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 674 | `nyc mocha && nyc report -r html mocha` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 674 | `mocha` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 671 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 689 | `mocha -R spec` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 689 | `mocha` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 689 | `mocha --check-leaks --reporter spec --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [shime/livedown](https://github.com/shime/livedown) | 682 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 681 | `mocha --require babel-register` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 681 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 677 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 676 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 675 | `node_modules/.bin/mocha` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 708 | `mocha tests/*.test.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 708 | `mocha` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 706 | `mocha -t 5000 -b -R spec test/index && npm run legacy-test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 705 | `mocha --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 704 | `./node_modules/.bin/mocha` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 703 | `tav --ci && mocha test/index.js` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 700 | `_mocha -u bdd --colors test/` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 700 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 696 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 674 | `nyc mocha && nyc report -r html mocha` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 674 | `mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 671 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 670 | `istanbul cover _mocha` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 669 | `mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 668 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 668 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 666 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [substance/data](https://github.com/substance/data) | 666 | `mocha -R spec tests/run.js` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 666 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 665 | `nyc mocha` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 665 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [DEgITx/rats-search](https://github.com/DEgITx/rats-search) | 662 | `mocha temp/tests.js --require @babel/core/lib --require source-map-support/register` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 662 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 661 | `mocha --recursive --compilers js:babel-core/register` | 